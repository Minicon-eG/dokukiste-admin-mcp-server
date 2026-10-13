# API coverage

Baseline: public DokuKiste OpenAPI 3.0.4, API v13.80.0, verified against backend commit `9406030dd34d04f05c6ae9e51e82811fe64dba08`. No controller or DTO API changes exist between v13.80.0 and this commit. Only the public API specification and reviewed route metadata are included; backend source code is not distributed.

This profile contains **527 reviewed HTTP operations**, including backward-compatible route aliases. The companion profile is disjoint. Read-only mode exposes only operations explicitly classified as read-only. The capabilities tool reports the actual instance version and available count.

Live mode loads the instance's specification on startup. Reviewed methods/routes must still exist; schemas come from that instance. Newly added or unreviewed methods/routes are not automatically exposed. The weekly contract workflow detects changed/removed inputs and new unreviewed routes. Update the reviewed policy before releasing support for new operations.

Browser login/registration/password flows, OAuth callbacks, webhook receivers and UI/infrastructure routes are deliberately excluded. Media and learning routes whose controller authorization is not part of the reviewed Web source are conservatively assigned to admin. The backend remains responsible for API-key scopes, feature flags, document visibility and tenant permissions; profile separation does not grant permission.

| Domain | Operations |
|---|---:|
| AccountingAccrual | 1 |
| AccountingAssets | 14 |
| AccountingEBilanz | 2 |
| AccountingExport | 2 |
| AccountingImport | 1 |
| AccountingMandant | 2 |
| AccountingOpos | 3 |
| AccountingProvision | 2 |
| AccountingReports | 6 |
| AccountingTypeConfiguration | 4 |
| AccountingVat | 2 |
| AccountingVatSplitCorrection | 1 |
| AccountingYearEnd | 4 |
| Admin | 18 |
| AdminAlerts | 4 |
| AiModels | 9 |
| AiProcessingConsent | 4 |
| AiProcessingConsentOverview | 1 |
| AiRoutingSettings | 6 |
| AnthropicSettings | 5 |
| ApiKeys | 7 |
| AppPdfCoSettings | 4 |
| AuditLogs | 3 |
| BackgroundJob | 8 |
| BankAccounts | 7 |
| BankHub | 5 |
| Banking | 10 |
| BankingAccountMerge | 3 |
| BankingContraAccount | 1 |
| BankingSevDesk | 3 |
| BugReport | 2 |
| ChartOfAccounts | 1 |
| ChatGptSettings | 5 |
| ComposeAssistantSettings | 6 |
| ConversationProviders | 5 |
| ConvertApiSettings | 4 |
| CostCenters | 11 |
| DocumentLogs | 1 |
| DocumentMetaMaintenance | 1 |
| DocumentTypes | 6 |
| DuplicateManagement | 3 |
| Duplicates | 5 |
| EmptyFieldsManagement | 4 |
| ExportLogs | 4 |
| FailedFieldSuggestions | 9 |
| FeatureModules | 16 |
| FeatureRequest | 3 |
| FieldInitialization | 6 |
| FieldMetadata | 3 |
| GeminiSettings | 4 |
| GetMyInvoicesSettings | 4 |
| GitHubSettings | 4 |
| GobdProcessDocumentation | 1 |
| HangfireQueue | 8 |
| Health | 1 |
| ImportLogs | 5 |
| InitializationJobs | 7 |
| InitializationQueue | 22 |
| InitializationReset | 2 |
| Integrations | 7 |
| IonosSettings | 4 |
| Learning | 11 |
| LexofficeSettings | 4 |
| LocalOcrSettings | 4 |
| MailAdminThreading | 1 |
| MailCompanyMatch | 1 |
| MailContactSummarySettings | 2 |
| MailDeliveryStatus | 1 |
| MailImportAudit | 1 |
| MailLinkRepair | 1 |
| MailOAuthSettings | 2 |
| MailOversize | 3 |
| Metrics | 7 |
| Minicon.Dokukiste.Web | 2 |
| MistralOcrSettings | 4 |
| OllamaSettings | 6 |
| Operations | 26 |
| PageContentRag | 4 |
| PageDiscovery | 7 |
| PdfCoCapabilities | 3 |
| PendingConflicts | 10 |
| PlanningCategoryTemplates | 5 |
| Prompts | 9 |
| SavedTree | 1 |
| ScheduledJobs | 17 |
| Security | 10 |
| SelfTest | 7 |
| SeqSettings | 4 |
| SevDeskAccountingTypes | 2 |
| SevDeskMappings | 6 |
| SevDeskSettings | 4 |
| Signature | 1 |
| SystemEmail | 3 |
| SystemMaintenance | 5 |
| TagColors | 4 |
| TagsMaintenance | 2 |
| TaxTypes | 3 |
| TextResolverChain | 5 |
| UserVisibility | 2 |
| Users | 18 |
| Video | 11 |
| VideoMedia | 1 |
| Workflows | 1 |
