# MailHog SMTP

___

## Setup

1. Clone this repository locally.

    ```sh
    git clone https://github.com/design-group/mailhog-smtp.git mailhog-smtp && cd mailhog-smtp
    ```

2. Pull any changes to the docker image and start the container.
      
    On Mac:
    
	```sh
    docker compose pull && docker compose up -d
    ```
    
	On WSL
    
	```sh
    docker-compose pull && docker-compose up -d
    ```