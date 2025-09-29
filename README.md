# OpenAI MCP Proxy

Một proxy server cho Model Context Protocol (MCP) kết nối với OpenAI API.

## Mô tả

Dự án này cung cấp một proxy server để xử lý các yêu cầu từ MCP client và chuyển tiếp chúng đến OpenAI API.

## Cài đặt

Clone repository này về máy của bạn:

```bash
git clone https://github.com/your-username/openai-mcp-proxy.git
cd openai-mcp-proxy
```

## Sử dụng

Cấu hình các biến môi trường cần thiết và khởi động server:

```bash
npm install
npm start
```

## Cấu hình

Copy file `.env.example` sang `.env` và điền các thông tin cần thiết:

- `OPENAI_API_KEY`: API key của bạn từ OpenAI
- `PORT`: Port mà server sẽ chạy (mặc định: 3000)

## Giấy phép

MIT License