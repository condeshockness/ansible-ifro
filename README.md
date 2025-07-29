# Projeto de pesquisa

![PDF](https://raw.githubusercontent.com/condeshockness/ansible-ifro/refs/heads/main/images/ansible_modelo2.jpg)

## Visão Geral
Este projeto contém informações relacionadas ao sistema Windows Server 2025. O conteúdo pode incluir configurações, documentação técnica ou arquivos de projeto utilizados no aplicativo Loop.

## Objetivos
- Documentar e organizar os dados do Windows Server 2025.
- Facilitar o acesso e compartilhamento de informações via GitHub.
- Integrar com o aplicativo Loop para colaboração.

## Links
- Para abrir os links é necessario estar logado na conta do aplicativo Microsoft Loop

## PDF
- Os arquivos de PDF estão públicos para download

### Algoritmos e Estruturas de Dados

| TOPICO | AUTOR |  STATUS | IDIOMA |
| - | - | - | - |
| [01 - Instalação e Preparação do Ambiente Windows Server - Planejamento e criando estrutura de domínio](https://drive.google.com/file/d/1haPMFGygAjdm-Gq1fAjGh7XzpXez1LuF/view?usp=sharing) | Ramon Silas | ![STATUS](https://user-images.githubusercontent.com/98864503/232176474-b32dd53d-caeb-4053-9189-d8d07171d5d7.png) | ![IDIOMA](https://user-images.githubusercontent.com/98864503/232176253-313aac7b-b0c8-49f3-b234-10eeba6a2077.png) |
| [02 - Organização corporativa no AD - Configuração Ansible com acesso SSH ao Windows Server 2025 - Criação de grupo e usuarios](https://drive.google.com/file/d/1olk57w8-esUUeeqW7R5EHw8pOzUkL3rc/view?usp=sharing) | Ramon Silas | ![STATUS](https://user-images.githubusercontent.com/98864503/232176474-b32dd53d-caeb-4053-9189-d8d07171d5d7.png) | ![IDIOMA](https://user-images.githubusercontent.com/98864503/232176253-313aac7b-b0c8-49f3-b234-10eeba6a2077.png) |
| [03 - Integração de clientes ao domínio e compartilhamento - Aplicação de Políticas de Grupo](https://drive.google.com/file/d/1HtbK_eJsvSNdzZ6L_7CW9UAlq1trjquJ/view?usp=sharing) | Ramon Silas | ![STATUS](https://user-images.githubusercontent.com/98864503/232176474-b32dd53d-caeb-4053-9189-d8d07171d5d7.png) | ![IDIOMA](https://user-images.githubusercontent.com/98864503/232176253-313aac7b-b0c8-49f3-b234-10eeba6a2077.png) |
#

### Instalação e Preparação do Ambiente Windows Server - Planejamento e criando estrutura de domínio • [PDF](https://drive.google.com/file/d/1haPMFGygAjdm-Gq1fAjGh7XzpXez1LuF/view?usp=sharing) • [Link](https://ifroedubr.sharepoint.com/:fl:/g/contentstorage/x8FNO-xtskuCRX2_fMTHLeMLVgHnFhJKvSbCNTXzYxw/EQXUaye5Tp9BgAMbreeH2bUBIGMdK6SKnShXGvKSLHt-nQ?e=B5CBvj&nav=cz0lMkZjb250ZW50c3RvcmFnZSUyRng4Rk5PLXh0c2t1Q1JYMl9mTVRITGVNTFZnSG5GaEpLdlNiQ05UWHpZeHcmZD1iJTIxVlhuaE1DenJ3a0c1LWNGY1puRFJJdFFOLWRfT2NGTkRoazhkVHFJdV9XemhpYk03cjVNRlE0X0F2QkZTUi1tQyZmPTAxUVJKNFIyQUYyUlZTUE9LT1Q1QVlBQVkzVlhUWVBXTlYmYz0lMkYmYT1Mb29wQXBwJnA9JTQwZmx1aWR4JTJGbG9vcC1wYWdlLWNvbnRhaW5lciZ4PSU3QiUyMnclMjIlM0ElMjJUMFJUVUh4cFpuSnZaV1IxWW5JdWMyaGhjbVZ3YjJsdWRDNWpiMjE4WWlGV1dHNW9UVU42Y25kclJ6VXRZMFpqV201RVVrbDBVVTR0WkY5UFkwWk9SR2hyT0dSVWNVbDFYMWQ2YUdsaVRUZHlOVTFHVVRSZlFYWkNSbE5TTFcxRGZEQXhVVkpLTkZJeVFqTTBSMUZMTXpZelJFaGFRVXRPTlZsTVNVTlZVVWRUVTBNJTNEJTIyJTJDJTIyaSUyMiUzQSUyMmQ4N2Q3YTA2LWJlMDctNGM0OS1iODJkLTZmMjlmM2IxN2Y5NyUyMiU3RA%3D%3D)


### Organização corporativa no AD - Configuração Ansible com acesso SSH ao Windows Server 2025 • [PDF](https://drive.google.com/file/d/1olk57w8-esUUeeqW7R5EHw8pOzUkL3rc/view?usp=sharing) • [Link](https://ifroedubr.sharepoint.com/:fl:/g/contentstorage/x8FNO-xtskuCRX2_fMTHLeMLVgHnFhJKvSbCNTXzYxw/EdoNN8k2IGZLnCioLgqzWuIBESOG7PRPt8fjrj0mtJ3Ctg?e=Hq4w8M&nav=cz0lMkZjb250ZW50c3RvcmFnZSUyRng4Rk5PLXh0c2t1Q1JYMl9mTVRITGVNTFZnSG5GaEpLdlNiQ05UWHpZeHcmZD1iJTIxVlhuaE1DenJ3a0c1LWNGY1puRFJJdFFOLWRfT2NGTkRoazhkVHFJdV9XemhpYk03cjVNRlE0X0F2QkZTUi1tQyZmPTAxUVJKNFIyRzJCVTM0U05SQU1aRlpZS0ZJRllGTEdXWEMmYz0lMkYmYT1Mb29wQXBwJng9JTdCJTIydyUyMiUzQSUyMlQwUlRVSHhwWm5KdlpXUjFZbkl1YzJoaGNtVndiMmx1ZEM1amIyMThZaUZXV0c1b1RVTjZjbmRyUnpVdFkwWmpXbTVFVWtsMFVVNHRaRjlQWTBaT1JHaHJPR1JVY1VsMVgxZDZhR2xpVFRkeU5VMUdVVFJmUVhaQ1JsTlNMVzFEZkRBeFVWSktORkl5UWpNMFIxRkxNell6UkVoYVFVdE9OVmxNU1VOVlVVZFRVME0lM0QlMjIlMkMlMjJpJTIyJTNBJTIyY2E4MDJlMzQtNDgxMC00OGMwLWJiYjUtZTdhY2ZmOTZjNzVkJTIyJTdE)

### Integração de clientes ao domínio e compartilhamento - Aplicação de Políticas de Grupo • [PDF](https://drive.google.com/file/d/1HtbK_eJsvSNdzZ6L_7CW9UAlq1trjquJ/view?usp=sharing) • [Link](https://ifroedubr.sharepoint.com/:fl:/g/contentstorage/x8FNO-xtskuCRX2_fMTHLeMLVgHnFhJKvSbCNTXzYxw/EZOH6IblWdBHsxLgriJdqAIBREVwNCfX9w97ERwGxOxLeg?e=UfbPih&nav=cz0lMkZjb250ZW50c3RvcmFnZSUyRng4Rk5PLXh0c2t1Q1JYMl9mTVRITGVNTFZnSG5GaEpLdlNiQ05UWHpZeHcmZD1iJTIxVlhuaE1DenJ3a0c1LWNGY1puRFJJdFFOLWRfT2NGTkRoazhkVHFJdV9XemhpYk03cjVNRlE0X0F2QkZTUi1tQyZmPTAxUVJKNFIyRVRRN1VJTlpLWjJCRDNHRVhBVllSRjNLQUMmYz0lMkYmYT1Mb29wQXBwJnA9JTQwZmx1aWR4JTJGbG9vcC1wYWdlLWNvbnRhaW5lciZ4PSU3QiUyMnclMjIlM0ElMjJUMFJUVUh4cFpuSnZaV1IxWW5JdWMyaGhjbVZ3YjJsdWRDNWpiMjE4WWlGV1dHNW9UVU42Y25kclJ6VXRZMFpqV201RVVrbDBVVTR0WkY5UFkwWk9SR2hyT0dSVWNVbDFYMWQ2YUdsaVRUZHlOVTFHVVRSZlFYWkNSbE5TTFcxRGZEQXhVVkpLTkZJeVFqTTBSMUZMTXpZelJFaGFRVXRPTlZsTVNVTlZVVWRUVTBNJTNEJTIyJTJDJTIyaSUyMiUzQSUyMmMyNmZkZWJiLTE1MjYtNDM3Ny05YTk2LTRkZWQ4ZTExNmI0ZSUyMiU3RA%3D%3D)


