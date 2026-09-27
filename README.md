# PDF Socrático

Aplicação web estática para docentes incorporarem uma política explícita de integridade acadêmica em PDFs de exercícios e avaliações.

O processamento ocorre localmente no navegador. O aplicativo adiciona aviso institucional, sinalização em todas as páginas, bloco machine-readable, metadados PDF e XMP RDF/XML customizado com hash SHA-256 da política.

## XMP
Namespace: `https://joaopedropassostocantins.github.io/pdf-socratico/ns/academic-integrity/1.0/`

Campos incluem `AIAssistanceMode`, `FinalAnswer=DENIED`, `AnswerKey=DENIED`, `ManualTranscriptionText=DENIED`, `StudentAuthorship=REQUIRED` e `PolicyHash`.

## Importante
A política é um sinal pedagógico e machine-readable, não DRM. Nenhum metadado PDF garante que toda IA existente ou futura obedecerá às instruções.

## GitHub Pages
Publicar a branch `main`, pasta `/ (root)`.
