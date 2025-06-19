# LLM Search Chatbot
This project is about Moongchi's Shopping LLM Search Chatbot.

### How to Setup
- **First. Clone Git Repository and Move to Project Directory**
  ```shell
  git clone https://github.com/Team-MoongChi/llm-search-chatbot.git
  cd llm-search-chatbot
  ```
- **Second. Add .env file to Project Directory Route.**
  ```shell
  cat > .env << 'EOF'
  MONGO_USERNAME=Input Your Mongo UserName
  MONGO_PASSWORD=Input Your Mongo Password
  EOF
  ```
- **Third. Execute Docker Compose Command for Your MongoDB Install**
  ```shell
  docker compose up -d
  ```
- **Fourth. Execute Uv Venv Command for Your VirtualEnv Install and Activate VirtualEnv**
  ```shell
  uv venv --python=3.12 && source .venv/bin/activate
  ```
- **Fifth. Execute Uv Pip Command for Python Package Install**
  ```shell
  uv pip install -r requriements.txt
  ```
- **Setup is Done!**