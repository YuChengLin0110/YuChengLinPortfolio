# YuChengLinPortfolio

## [AI-Integration-Service](https://github.com/YuChengLin0110/AI-Integration-Service)
AI-Integration-Service 是一個可擴充的 RAG（Retrieval-Augmented Generation）與多模型 AI 整合，支援 OpenAI、Gemini 等 LLM

透過文件上傳、切段、Embedding、向量檢索與語意問答等流程，提供知識檢索與智慧客服能力

系統中的各個元件都透過 策略模式（Strategy Pattern）＋ 工廠模式（Factory Pattern） 管理，可以依需求自由替換向量庫、Embedding 模型或 LLM

AI-Integration-Service is a flexible RAG (Retrieval-Augmented Generation) and multi-LLM integration platform.

It supports models like OpenAI and Gemini, and lets you upload documents, chunk text, create embeddings, search vectors, and perform accurate Q&A.

All core components use the Strategy Pattern + Factory Pattern, so you can easily swap the vector store, embedding model, or LLM provider based on your needs.

## [TaskManager](https://github.com/YuChengLin0110/Taskmanager)
TaskManager 是一個簡潔的分布式任務管理系統，基於 Spring Boot，整合 Spring Cloud Config、RabbitMQ、Kafka、Redis 等技術

實現任務追蹤、狀態管理、非同步處理與通知機制，支援 JWT 認證、分布式鎖、批量 DB 操作及主從資料庫讀寫分離，並可透過 Docker 容器化部署

TaskManager is a lightweight distributed task management system built with Spring Boot, integrating Spring Cloud Config, RabbitMQ, Kafka, Redis, and other technologies.

It provides task tracking, status management, asynchronous processing, and notification support, with JWT authentication, distributed locks, batch database operations, and master-slave database read/write separation. 

It can also be deployed using Docker containers.

## [DS-Algorithms](https://github.com/YuChengLin0110/DS-Algorithms)
這是我用來學習資料結構與演算法的專案，包含了 LinkedList、Graph、Tree 等資料結構與演算法的實作。

This is a project where I learn data structures and algorithms, including LinkedList, Graph, Tree, and other data structures and algorithms.

## [ConcurrentBankDemo](https://github.com/YuChengLin0110/ConcurrentBankDemo)
這個專案是我學習 Java 多執行緒的練習，模擬銀行轉帳功能，並使用 ExecutorService 等工具進行多執行緒管理。

This project is for learning Java multithreading. It simulates a bank transfer system and uses ExecutorService to manage multiple threads.

## [Shop](https://github.com/YuChengLin0110/Shop)
這是我於 2023 年使用 Spring Boot 所開發的簡單購物網站，雖然目前不再更新，但它幫助我加深了對 Spring Boot 的理解，留做紀錄。

This is a simple shopping website I built with Spring Boot in 2023. It is no longer updated, but it helped me learn more about Spring Boot, and I keep it as a record.


## [Shop-Cloud](https://github.com/YuChengLin0110/Shop-Cloud)
這是我 2023 年進一步基於 Spring Boot 所開發的雲端購物平台，與 Shop 專案相似，但使用了更多雲端技術與部署，目前也不再更新，留做紀錄。

This is a cloud-based shopping platform I built with Spring Boot in 2023. It is similar to the Shop project, but with more cloud technology and deployment. It is no longer updated, and I keep it as a record.
