# OCRLLM - Document Processing and Retrieval-Augmented Generation

🌐 Language / 言語

- 🇺🇸 **English** → [README.en.md](README.en.md)
- 🇯🇵 **日本語** → [README.ja.md](README.ja.md)

---

Retrieval-Augmented Generation (RAG) microservice designed for processing, embedding, and querying documents. 
It integrates document parsing, semantic search, knowledge graph construction, and LLM-based generation to provide advanced document intelligence. Built with scalability in mind, it uses PostgreSQL for session management, Qdrant for vector storage, Dgraph for graph-based indexing, and Celery for asynchronous task processing.


ドキュメントの処理、埋め込み（embedding）、およびクエリ実行を行うために設計された、RAG（検索拡張生成）対応のマイクロサービスです。
ドキュメントの解析、セマンティック検索、ナレッジグラフの構築、そしてLLM（大規模言語モデル）による生成機能を統合し、高度なドキュメント・インテリジェンスを実現します。スケーラビリティを考慮して構築されており、セッション管理にはPostgreSQL、ベクトルストレージにはQdrant、グラフベースのインデックス作成にはDgraph、非同期タスク処理にはCeleryを採用しています。
