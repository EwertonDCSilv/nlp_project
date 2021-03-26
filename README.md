# Universidade Federal de Minas Gerais
# Projeto final: Predizendo produtos por meio de reclamações textuais - 2020/2
**Resumo**: objetivo é criar um modelo Sequence-to-Sequence usando uma rede LSTM, o qual que preveja produtos financeiros por meio de uma reclamação textuais de consumidores ao "Departamento de Proteção Financeira do Consumidor" dos EUA. O corpus está disponível em https://catalog.data.gov/dataset/consumer-complaint-database. 

**Sobre o Dataset**: "The Consumer Complaint Database is a collection of complaints about consumer financial products and services that we sent to companies for response. Complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first. Complaints referred to other regulators, such as complaints about depository institutions with less than $10 billion in assets, are not published in the Consumer Complaint Database. The database generally updates daily." [SIC]

**Baixar do GitHub**: https://github.com/EwertonDCSilv/nlp_final_project \
**Executar no colab**: https://drive.google.com/drive/folders/1necRI2e-UNhp30eUqaEyp5ColWeZKN02?usp=sharing \
**Link do vídeo no Drive** https://drive.google.com/drive/folders/18sVyH1lXZ9NvnQ2qMadnqUwqN-9EU92M?usp=sharing \
**Link do vídeo no YouTube**  https://youtu.be/ae-_LakbDsE

**Pastas**:
```
.
+-- data
|   +-- Consumer_Complaints.zip // Conjunto de teste com apenas 20 mil entradas
|   +-- Consumer_Complaints_Full.zip // Conjunto completo de dados
+-- model // Pasta para exportar modelo 
|   +-- saved_model.pb
|   +-- _variables
|   |   +-- variables.data-00000-of-00001
|   |   +-- variables.index
+-- README.md
+-- tpFinal.ipynb // Codigo
```
