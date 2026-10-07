
# Progresso do projeto

## 06/10/2026

### Customer
- CRUD de Customer estruturado
- Validação de CPF duplicado funcionando
- Tratamento de erro implementado
- Ajuste do ShowOnlyFirstError
- Testes de cadastro realizados

### Arquitetura
- Uso de Service Actions
- Separação entre validação e persistência
- Testes de fluxo de criação e edição

## 07/10/2026

### Device Core
- Relacionamento Customer → Device revisado
- Device_SaveCore criado
- Device_Validation criado
- Validações de cliente, tipo, marca e modelo implementadas
- Validação de Serial Number duplicado implementada
- Device_Save criado
- Device_SoftDelete criado
- Auditoria de CreatedOn, CreatedBy, UpdatedOn e UpdatedBy mantida

### Device UI
- DeviceList criada
- Listagem de equipamentos por cliente funcionando
- DeviceDetail criada
- Cadastro de novos equipamentos funcionando
- Edição de equipamentos funcionando
- SoftDelete funcionando
- Validações exibidas corretamente na interface
- Integração Customer → Device testada
- Testes de criação, edição, duplicidade de serial e desativação concluídos com sucesso

### Arquitetura
- Mantido o padrão Trusted Academy já utilizado no Customer
- Separação entre Validation, Save, SaveCore e SoftDelete
- Reaproveitamento do mesmo padrão de Exception Handler e tratamento de erros

## Próximos passos

- Documentar o CRUD de Device com screenshots
- Atualizar o README do projeto
- Iniciar o módulo de ServiceOrder
- Definir geração e exibição do número da Ordem de Serviço
- Criar ServiceOrder_SaveCore
- Criar ServiceOrder_Validation
- Criar ServiceOrder_Save
- Criar ServiceOrder_SoftDelete
