# AI Changelog

## 2025-05-15

- Updated `concepts/product.mdx` to align product properties with SDK enums and clarify SDK integration, including new code examples.
- Updated `concepts/product/version.mdx` to clarify `optional_props` keys for version creation.
- Updated `concepts/product/test.mdx` to document `language`, `variants`, and `max_test_cases` fields.
- Updated `concepts/product/test/case.mdx` to clarify `tag`, `source`, and add `conversation_turns`.
- Updated `concepts/product/evaluation/task.mdx` to document all SDK parameters, including deprecated fields, `conversation_turns`, and `scores`.
- Updated `concepts/metric-type.mdx` to clarify `evaluation_params` and add `source` and `definition` fields.
- Updated `sdk/api/product-service.mdx` to document `get_by_name` method.
- Updated `sdk/api/version-service.mdx` to expand `optional_props` documentation.
- Updated `sdk/api/test-service.mdx` to fully document `variants`, `language`, and `max_test_cases`.
- Updated `sdk/api/test-case-service.mdx` to add and document `tag` parameter.
- Updated `sdk/api/metrics-service.mdx` to clarify `evaluation_params` usage and values.
- Updated `sdk/api/evaluation-task-service.mdx` to fully document all parameters for `create` and `create_from_production`, including deprecated fields and new additions.
- Updated `sdk/examples/create-evaluation.mdx` to correct usage of `retrieval_context`, `usage_info`, and `cost_info`, and add deprecation warning for direct input/context/expected_output.
- Updated `sdk/examples/monitor-production-responses-to-user-queries.mdx` to ensure correct `conversation_turns` format and snake_case info dicts.
- Updated `quickstart.mdx` to improve code snippets for accuracy and best practices, and to clarify use of `your_product_function`.

These changes ensure the Galtea documentation accurately reflects the SDK's capabilities and best practices as of May 2025.
