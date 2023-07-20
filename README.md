# TabelaCoresequantidadeSQL
# Neste código, estamos criando uma tabela chamada "cores" com duas colunas: "cor" e "quantidade".

-- Criar a tabela "cores"
CREATE TABLE cores (
    cor VARCHAR(10),
    quantidade INT
);

-- Inserir os dados
INSERT INTO cores (cor, quantidade) VALUES
    ('azul', 50),
    ('branco', 20),
    ('vermelho', 15);

