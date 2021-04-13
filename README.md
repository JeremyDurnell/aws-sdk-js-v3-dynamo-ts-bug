The following commands will produce typescript errors - included at the end of this document.

```bash
yarn && yarn tsc
```

### Errors

```bash
$ tsc
node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/BatchExecuteStatementCommand.d.ts:24:22 - error TS2515: Non-abstract class 'BatchExecuteStatementCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<BatchExecuteStatementCommandInput, BatchExecuteStatementCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

24 export declare class BatchExecuteStatementCommand extends $Command<BatchExecuteStatementCommandInput, BatchExecuteStatementCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/BatchGetCommand.d.ts:35:22 - error TS2515: Non-abstract class 'BatchGetCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<BatchGetCommandInput, BatchGetCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

35 export declare class BatchGetCommand extends $Command<BatchGetCommandInput, BatchGetCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/BatchWriteCommand.d.ts:51:22 - error TS2515: Non-abstract class 'BatchWriteCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<BatchWriteCommandInput, BatchWriteCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

51 export declare class BatchWriteCommand extends $Command<BatchWriteCommandInput, BatchWriteCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/DeleteCommand.d.ts:36:22 - error TS2515: Non-abstract class 'DeleteCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<DeleteCommandInput, DeleteCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

36 export declare class DeleteCommand extends $Command<DeleteCommandInput, DeleteCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/ExecuteStatementCommand.d.ts:20:22 - error TS2515: Non-abstract class 'ExecuteStatementCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<ExecuteStatementCommandInput, ExecuteStatementCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

20 export declare class ExecuteStatementCommand extends $Command<ExecuteStatementCommandInput, ExecuteStatementCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/ExecuteTransactionCommand.d.ts:24:22 - error TS2515: Non-abstract class 'ExecuteTransactionCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<ExecuteTransactionCommandInput, ExecuteTransactionCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

24 export declare class ExecuteTransactionCommand extends $Command<ExecuteTransactionCommandInput, ExecuteTransactionCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/GetCommand.d.ts:22:22 - error TS2515: Non-abstract class 'GetCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<GetCommandInput, GetCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

22 export declare class GetCommand extends $Command<GetCommandInput, GetCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/PutCommand.d.ts:36:22 - error TS2515: Non-abstract class 'PutCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<PutCommandInput, PutCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

36 export declare class PutCommand extends $Command<PutCommandInput, PutCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/QueryCommand.d.ts:38:22 - error TS2515: Non-abstract class 'QueryCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<QueryCommandInput, QueryCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

38 export declare class QueryCommand extends $Command<QueryCommandInput, QueryCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/ScanCommand.d.ts:33:22 - error TS2515: Non-abstract class 'ScanCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<ScanCommandInput, ScanCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

33 export declare class ScanCommand extends $Command<ScanCommandInput, ScanCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/TransactGetCommand.d.ts:28:22 - error TS2515: Non-abstract class 'TransactGetCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<TransactGetCommandInput, TransactGetCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

28 export declare class TransactGetCommand extends $Command<TransactGetCommandInput, TransactGetCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/TransactWriteCommand.d.ts:57:22 - error TS2515: Non-abstract class 'TransactWriteCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<TransactWriteCommandInput, TransactWriteCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

57 export declare class TransactWriteCommand extends $Command<TransactWriteCommandInput, TransactWriteCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~~~~~~~~

node_modules/@aws-sdk/lib-dynamodb/dist/types/commands/UpdateCommand.d.ts:41:22 - error TS2515: Non-abstract class 'UpdateCommand' does not implement inherited abstract member 'resolveMiddleware' from class 'Command<UpdateCommandInput, UpdateCommandOutput, DynamoDBDocumentClientResolvedConfig, any, any>'.

41 export declare class UpdateCommand extends $Command<UpdateCommandInput, UpdateCommandOutput, DynamoDBDocumentClientResolvedConfig> {
                        ~~~~~~~~~~~~~


Found 13 errors.

error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
