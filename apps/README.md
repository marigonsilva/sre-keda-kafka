 kubectl run consumer --rm --tty -i --image marigonsilva/consumer:latest --image-pull-policy Never --restart Never --namespace kafkaplaypen --command -- python3 -u ./consumer.py


 kubectl run consumer --rm --tty -i --image marigonsilva/producer:latest --image-pull-policy Never --restart Never --namespace kafkaplaypen --command -- python3 -u ./producer.py
