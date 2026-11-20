# CASE-API_Simple-Network-Search
CASE-API之简单联网搜索：对 DashScope 平台来说，加`extra_body={"enable_search": True}` 就是开启联网搜索的标准做法 ，非常方便——比自己实现 Agent + 搜索工具要简单得多。如果你需要更灵活的搜索控制（比如指定搜索来源、搜索范围），那就要用 Function Calling / Agent 的方式自己封装搜索工具
