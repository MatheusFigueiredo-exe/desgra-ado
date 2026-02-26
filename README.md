
# Projeto: Tela de Login

### Descrição

Exemplo simples de uma tela de login construída com Bootstrap 5. Este projeto serve como template/estudo para criar um formulário de autenticação responsivo e estilizado.

**Autor:** Abner Matheus — https://github.com/MatheusFigueiredo-exe

### Como usar

- Abra o arquivo `index.html` no navegador (duplo-clique). Para servir localmente com um servidor HTTP simples, execute:

```bash
python -m http.server 8000
# então abra http://localhost:8000
```

Ou use a extensão Live Server do VS Code para um reload automático.

### Estrutura do projeto

- `index.html` — página principal contendo o formulário de login.
- `sign-in.css` — estilos personalizados para a página.
- `README.md` — este arquivo.

### Personalização

- Altere cores, fontes e espaçamentos editando `sign-in.css`.
- Para adicionar validação ou integração com backend, conecte o formulário a um endpoint POST.

### Créditos

- Template e componentes baseados nos exemplos oficiais do Bootstrap 5.

### FAQ (Perguntas Frequentes)

- **Como eu abro este projeto no meu computador?**

	Basta abrir `index.html` no navegador. Para servir os arquivos via HTTP (útil para recursos relativos), execute `python -m http.server 8000` e abra `http://localhost:8000`.

- **Posso alterar o visual da página?**

	Sim — edite `sign-in.css` para ajustar cores, fontes e espaçamento. Você também pode substituir classes do Bootstrap por utilitários diferentes conforme necessário.

- **Como valido o formulário antes de enviar?**

	Você pode usar validação HTML5 (atributos `required`, `type=email`) ou adicionar validação JavaScript personalizada no evento de submit do formulário.

- **Como conecto o formulário a um backend?**

	Defina o atributo `action` do formulário para o endpoint desejado e o `method` (normalmente `POST`). Para chamadas assíncronas, faça um `fetch()` ou use Axios para enviar os dados JSON ao servidor.

- **Funciona em dispositivos móveis?**

	Sim — o layout foi construído com Bootstrap 5 e é responsivo por padrão. Teste em diferentes larguras de tela e ajuste classes/utilitários quando necessário.

- **Posso usar este template em projetos comerciais?**

	Sim, o projeto está licenciado sob MIT (ver seção Licença). Verifique dependências externas e suas licenças também.

### Licença

Este projeto está disponível sob a licença MIT. Use à vontade e adapte conforme necessário.

