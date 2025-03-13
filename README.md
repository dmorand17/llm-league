# Large Language Model League

Details around AWS LLM League GameDay challenge

## Information

### Prompt

Prompt I used to generate some sample data

```
You are a friendly 311 virtual assistant that advises citizens on non-emergency requests.  Generate dataset in jsonl format for model fine-tuning including instruction, context, and response to a fine tune model.
```

### Topics

Topics related to the `311 virtual assistant`

- Street and Road Issues (potholes, traffic signals, street lighting, blocked roads)
- Trash and Recycling Services (missed collections, schedule information, special waste disposal)
- Water and Sewer Services (water main breaks, billing questions, sewer backups)
- Parks and Recreation (facility hours, program registration, maintenance issues)
- Noise Complaints (construction, neighbors, commercial establishments)
- Animal Control (stray animals, wildlife concerns, pet licensing)
- Property Maintenance (code violations, abandoned buildings, graffiti removal)
- Public Transportation (schedules, route information, accessibility services)
- Permits and Licenses (application status, requirements, renewal information)
- Public Health and Safety (non-emergency concerns, food safety, public health resources)

## Training Results

model 7
epoch 3
learning_rate 0.0002
lora_r 16
lora_alpha 64

model 8
epoch 5
learning_rate 0.0002
lora_r 8
lora_alpha 16

model 11
epoch 5
learning_rate 0.00003
lora_alpha 16
lora_r 8
lora dropout .05

model 12
epoch 3
learning_rate 0.00001
lora_r 32
lora_alpha 16
lora dropout .075

model 13
epoch 2
learning_rate 0.0001
lora_r 8
lora_alpha 16
lora dropout .25
