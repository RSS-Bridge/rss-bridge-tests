## Pull request artifacts
| Bridge | Context | Status |
| - | - | - |
| Instagram | [1 Username (current)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_1_current.html) | ❌ `Bridge returned error 0! (20505)`<br>❌ `Type: ErrorException`<br>❌ `Message: Undefined property: stdClass::$data` |
| Instagram | [1 Username (pr)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_1_pr.html) | ❌ `Bridge returned error 0! (20505)`<br>❌ `Type: ErrorException`<br>❌ `Message: Undefined property: stdClass::$data` |
| Instagram | [2 Hashtag (current)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_2_current.html) | ❌ `Bridge returned error 401! (20505)`<br>❌ `Type: HttpException`<br>❌ `Message: https://www.instagram.com/graphql/query/?query_hash=9b498c08113f1e09617a1703c22b2f32&variables={"tag_name"%3A"beautifulday"%2C"first"%3A10} resulted in 401 Unauthorized` |
| Instagram | [2 Hashtag (pr)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_2_pr.html) | ❌ `Bridge returned error 401! (20505)`<br>❌ `Type: HttpException`<br>❌ `Message: https://www.instagram.com/graphql/query/?query_hash=9b498c08113f1e09617a1703c22b2f32&variables={"tag_name"%3A"beautifulday"%2C"first"%3A10} resulted in 401 Unauthorized` |
| Instagram | [3 Location (current)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_3_current.html) | ⚠️ `The feed has no items` |
| Instagram | [3 Location (pr)](https://RSS-Bridge.github.io/rss-bridge-tests/prs/4908/Instagram_3_pr.html) | ⚠️ `The feed has no items` |

*last change: Saturday 2026-02-21 18:40:58*