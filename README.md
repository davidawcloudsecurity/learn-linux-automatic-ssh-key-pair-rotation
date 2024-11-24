# learn-linux-automatic-ssh-key-pair-rotation
### How to use systems manager to rotate ssh keys
```bash
ssh-keygen -f example.pem -t rsa
cat example.pem.pub
```
```bash
echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDcmQyBaAXda4MP9b5nSUubB+eUUjhVEIJaif7bTcnMa+l8octMYWTgl8QC1aQOwI5/Z7m0NlbuGHMu66qOplWT2Js4bvFxBFjWfNfmUFCKP6Teas22m8nfwryfvQS2bP0V0VSWu6AiJ6QqdOumBZkFvpvW5IZ4TEJ7e1iaiiTu5rreP9IBrYjrl8jXLLc5pxIXt79RUKmD8js0KW1M7LgcswH+ITc2UQFDq7D7Dgg2Tyv+5QlubSIDWT3suuh6MlLX/hU4tGX8le5Le2RBr/Ue5b5eQ4g5gFSzuLVVN18dTNSlvT6hRpBl6x/8s/Hds8/LDBm8Z38/MZTs0ndAtWAb test-key-transfer01" > /home/ubuntu/.ssh/authorized_keys
```
