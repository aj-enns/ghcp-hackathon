# Exercise 1: Database Schema to Code

⬅️ Previous: None | ➡️ Next: [02-architecture-diagram.md](02-architecture-diagram.md)

---

## Instructions

1. Open GitHub Copilot Chat (`Ctrl+Shift+I` or `Cmd+Shift+I`)
2. Click the 📎 **attachment button** in the chat input
3. Select **`DB-Schema.png`** from the repo root
4. Copy the prompt below and paste it into Copilot Chat
5. Press Enter and watch Copilot analyze the image!

---

## Prompt

Using the attached database schema image, create the SQL DDL statements to build this database. Include:

1. All tables with proper data types
2. Primary keys and foreign key relationships  
3. Appropriate indexes for common queries
4. Comments explaining each table's purpose

---

## Follow-up Prompts

Try these after the initial response:

- "Now generate Entity Framework Core models in C# for this schema"
- "Create Python SQLAlchemy ORM mappings for these tables"
- "Generate sample INSERT statements with realistic test data"
- "What indexes would you recommend for optimizing read-heavy queries?"
