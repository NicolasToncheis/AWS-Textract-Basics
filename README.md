# AWS-Textract-Basics
Repository for the lessons learned on the bootcamp "Advanced Image and Text Analysis with AI", by a colab with AWS and Nexa.

Eu achei muito interessante a abordagem do Professor Guilherme em verificar passo-a-passo a montagem do código, com viés na DOCUMENTAÇÃO oficial, algo que, realizando sozinho, talvez nunca fosse compreender tão bem. Para esse projeto, eu decidi exibir prints do código desenvolvido nas aulas e no desafio, junto com comentários meus dentro dele.

Para exibir o código, utilizei um ambiente do Colab, com o qual tenho maior facilidade em acessar:
![image](https://github.com/user-attachments/assets/becf4fe2-3d1b-43d2-b178-08bde8cc7387) #Importação das bibliotecas utilizadas no começo das aulas.

![image](https://github.com/user-attachments/assets/fc528358-94a0-4520-92c7-2461ead71410) #Chamada do documento a ser analisado, transformado em bytes e descrição do def que gera a análise de documento com base no tipo especificado pelo Feature Type.

![image](https://github.com/user-attachments/assets/008ef9fe-c11c-4bbf-b71f-9fb4aa63e445) #Definição do relacionamento entre variáveis de chave e valor, e também a determinação da relação entre eles por meio do ID, conforme a documentação oficial.

![image](https://github.com/user-attachments/assets/32e8c24b-dff0-468a-810b-d275ccb16be1) #Armazenamento dessa relação como texto concatenado e, por fim, a exibição dele, de forma que foi possível abordar o caso para uma CNH, porém, também pode ser feito para demais documentos oficiais, como passaportes, RGs, carteiras de trabalho e afins.

![image](https://github.com/user-attachments/assets/c8045edd-1c00-47ce-b981-655d7340adc0) #Bibliotecas adicionais necessárias para conseguir extrair os itens da lista de materiais, junto com o código para a opção de ler o documento já em bytes, pelo tipo de arquivo detectado automaticamente pelo Textract.

![image](https://github.com/user-attachments/assets/7d422e91-e9ac-498a-a293-e2c83d012fcb) #Por fim, fazer uma interpretação direta do documento como um elemento de lista, uma vez que está sendo analisada linha a linha do documento. Não ideal para casos mais gerais (como lista em quadrantes, por exemplo).

