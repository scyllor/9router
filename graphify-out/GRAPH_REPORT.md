# Graph Report - 9router  (2026-05-04)

## Corpus Check
- 505 files · ~382,883 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 2070 nodes · 3864 edges · 44 communities detected
- Extraction: 70% EXTRACTED · 30% INFERRED · 0% AMBIGUOUS · INFERRED: 1147 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]

## God Nodes (most connected - your core abstractions)
1. `POST()` - 179 edges
2. `GET()` - 150 edges
3. `log()` - 86 edges
4. `DELETE()` - 63 edges
5. `get()` - 63 edges
6. `getDb()` - 53 edges
7. `error()` - 47 edges
8. `find()` - 45 edges
9. `warn()` - 42 edges
10. `info()` - 39 edges

## Surprising Connections (you probably didn't know these)
- `parseEventFrame()` --calls--> `warn()`  [INFERRED]
  open-sse\executors\kiro.js → src\sse\utils\logger.js
- `POST()` --calls--> `getProviderModels()`  [INFERRED]
  src\app\api\version\update\route.js → open-sse\config\providerModels.js
- `findModelName()` --calls--> `find()`  [INFERRED]
  open-sse\config\providerModels.js → open-sse\rtk\filters\find.js
- `getModelQuotaFamily()` --calls--> `find()`  [INFERRED]
  open-sse\config\providerModels.js → open-sse\rtk\filters\find.js
- `handleImageGenerationCore()` --calls--> `urlToBase64()`  [INFERRED]
  open-sse\handlers\imageGenerationCore.js → open-sse\handlers\imageProviders\_base.js

## Communities

### Community 0 - "Community 0"
Cohesion: 0.02
Nodes (117): clearAccountError(), resetComboRotation(), clearConsoleLogs(), formatArg(), getConsoleEmitter(), getConsoleLogs(), stripAnsi(), DroidToolCard() (+109 more)

### Community 1 - "Community 1"
Cohesion: 0.02
Nodes (85): downloadFile(), ensureCloudflared(), getDownloadStatus(), getDownloadUrl(), isCloudflaredRunning(), isValidBinary(), killCloudflared(), killCloudflaredByPort() (+77 more)

### Community 2 - "Community 2"
Cohesion: 0.03
Nodes (116): intercept(), showBanner(), showSimpleBanner(), fetchRouter(), pipeSSE(), callCloudWithMachineId(), getCloudUrl(), startProviderSync() (+108 more)

### Community 3 - "Community 3"
Cohesion: 0.04
Nodes (99): applyErrorState(), buildModelLockUpdate(), checkFallbackError(), formatRetryAfter(), getEarliestRateLimitedUntil(), getModelLockKey(), getQuotaCooldown(), getUnavailableUntil() (+91 more)

### Community 4 - "Community 4"
Cohesion: 0.03
Nodes (84): del(), get(), handleResponse(), post(), put(), claudeToOpenAIResponse(), convertStopReason(), createChunk() (+76 more)

### Community 5 - "Community 5"
Cohesion: 0.03
Nodes (60): buildUserContent(), getProviderLabel(), humanize(), makeSessionTitle(), normalizeLiveModel(), normalizeStaticModel(), textValue(), normalizeLegacyProxy() (+52 more)

### Community 6 - "Community 6"
Cohesion: 0.03
Nodes (31): AntigravityService, ClaudeService, CloudSyncScheduler, CodexService, handleForwardRaw(), GeminiCLIService, IFlowService, isCloudEnabled() (+23 more)

### Community 7 - "Community 7"
Cohesion: 0.04
Nodes (62): safeApply(), autoDetectFilter(), countMatches(), isLineNumbered(), isMostlyPorcelain(), appendToOpenAIMessage(), injectCaveman(), injectClaudeSystem() (+54 more)

### Community 8 - "Community 8"
Cohesion: 0.04
Nodes (46): buildKimiHeaders(), geminiCLIUserAgent(), cacheClaudeHeaders(), getCachedClaudeHeaders(), isClaudeCodeClient(), buildClineHeaders(), getClineAccessToken(), getClineAuthorizationHeader() (+38 more)

### Community 9 - "Community 9"
Cohesion: 0.04
Nodes (30): Avatar(), Badge(), Button(), Card(), cn(), Drawer(), getLocaleFromCookie(), HeaderMenu() (+22 more)

### Community 10 - "Community 10"
Cohesion: 0.06
Nodes (48): createNonStreamingResponse(), createOpenAIResponse(), createOpenAIStreamingChunks(), createStreamingResponse(), handleBypassRequest(), mergeChunksToResponse(), claudeToOpenAIRequest(), convertClaudeMessage() (+40 more)

### Community 11 - "Community 11"
Cohesion: 0.06
Nodes (37): createErrorResponse(), CursorExecutor, debugLog(), decompressPayload(), buildCursorHeaders(), generateCursorChecksum(), generateHashed64Hex(), generateSessionId() (+29 more)

### Community 12 - "Community 12"
Cohesion: 0.08
Nodes (33): buildBraveRequest(), buildExaRequest(), buildGooglePseRequest(), buildLinkupRequest(), buildPerplexityRequest(), buildSearchApiRequest(), buildSearchRequest(), buildSearxngRequest() (+25 more)

### Community 13 - "Community 13"
Cohesion: 0.06
Nodes (16): CodexExecutor, extractItemText(), generateSessionId(), hashContent(), resolveConversationSessionId(), GithubExecutor, clampCallId(), openaiResponsesToOpenAIRequest() (+8 more)

### Community 14 - "Community 14"
Cohesion: 0.1
Nodes (30): cleanJSONSchemaForAntigravity(), convertConstToEnum(), convertEnumValuesToStrings(), convertOpenAIContentToParts(), flattenAnyOfOneOf(), flattenTypeArrays(), generateProjectId(), generateRequestId() (+22 more)

### Community 15 - "Community 15"
Cohesion: 0.09
Nodes (26): buildNonStreamingResponse(), buildStreamingResponse(), generateStatsigId(), GrokWebExecutor, parseOpenAIMessages(), randomHex(), randomString(), buildCursorRequest() (+18 more)

### Community 16 - "Community 16"
Cohesion: 0.1
Nodes (3): AntigravityExecutor, BaseExecutor, resolveOllamaLocalHost()

### Community 17 - "Community 17"
Cohesion: 0.1
Nodes (10): KiroExecutor, parseEventFrame(), buildQwenUpstreamHeaders(), ensureQwenSystemMessage(), isQwenThinkingActive(), QwenExecutor, sanitizeQwenThinkingToolChoice(), resolveRetryEntry() (+2 more)

### Community 18 - "Community 18"
Cohesion: 0.16
Nodes (18): parseModelVoice(), responseToBase64(), throwUpstreamError(), cartesia(), coqui(), deepgram(), huggingface(), hyperbolic() (+10 more)

### Community 19 - "Community 19"
Cohesion: 0.11
Nodes (10): getErrorCode(), ApiKeyProviderCard(), ComboList(), getConnectionErrorTag(), getEffectiveStatus(), getStatusDisplay(), MediaProviderKindPage(), ProviderCard() (+2 more)

### Community 20 - "Community 20"
Cohesion: 0.16
Nodes (13): parseResponse(), parseResponse(), parseResponse(), parseResponse(), finalize(), isAppPortBusy(), persistStatus(), pushLog() (+5 more)

### Community 21 - "Community 21"
Cohesion: 0.15
Nodes (6): nowSec(), urlToBase64(), buildSseResponse(), parseResponse(), parseStream(), parseResponse()

### Community 22 - "Community 22"
Cohesion: 0.33
Nodes (12): closeMessage(), closeReasoning(), closeToolCall(), computeFinishReason(), emitReasoningDelta(), emitTextContent(), emitToolCall(), flushEvents() (+4 more)

### Community 23 - "Community 23"
Cohesion: 0.24
Nodes (9): getPageInfo(), Header(), getLocaleFromCookie(), initRuntimeI18n(), loadTranslations(), processElement(), processTextNode(), reloadTranslations() (+1 more)

### Community 24 - "Community 24"
Cohesion: 0.38
Nodes (9): formatGitHubQuotaSnapshot(), getAntigravityUsage(), getClaudeUsage(), getCodexUsage(), getGeminiUsage(), getGitHubUsage(), getIflowUsage(), getQwenUsage() (+1 more)

### Community 25 - "Community 25"
Cohesion: 0.39
Nodes (8): collectAppPids(), ensureRuntimeUpdater(), getDataDir(), killAppProcesses(), killMitmByPidFile(), resolveBundledUpdaterPath(), resolveRelaunchCommand(), spawnUpdaterAndExit()

### Community 26 - "Community 26"
Cohesion: 0.32
Nodes (1): IFlowExecutor

### Community 27 - "Community 27"
Cohesion: 0.33
Nodes (1): QoderExecutor

### Community 29 - "Community 29"
Cohesion: 0.38
Nodes (3): fmt(), fmtCost(), ValueCells()

### Community 30 - "Community 30"
Cohesion: 0.38
Nodes (3): logOffset(), readLogSince(), waitForRtkLine()

### Community 31 - "Community 31"
Cohesion: 0.33
Nodes (1): AzureExecutor

### Community 32 - "Community 32"
Cohesion: 0.53
Nodes (5): fetchLocalDeviceVoices(), fetchVoicesMac(), fetchVoicesWin(), synthesize(), synthesizeMacOrWin()

### Community 33 - "Community 33"
Cohesion: 0.47
Nodes (3): normalizePresets(), readPresets(), writePresets()

### Community 36 - "Community 36"
Cohesion: 0.4
Nodes (1): OpenCodeExecutor

### Community 37 - "Community 37"
Cohesion: 0.6
Nodes (3): getToken(), synthesize(), ttsRequest()

### Community 38 - "Community 38"
Cohesion: 0.7
Nodes (4): antigravityToOpenAIRequest(), convertContent(), extractText(), normalizeSchemaTypes()

### Community 41 - "Community 41"
Cohesion: 0.83
Nodes (3): convertGeminiContent(), extractGeminiText(), geminiToOpenAIRequest()

### Community 42 - "Community 42"
Cohesion: 0.67
Nodes (2): ComboDetailPage(), getListingHref()

### Community 43 - "Community 43"
Cohesion: 0.83
Nodes (3): fmt(), fmtCost(), OverviewCards()

### Community 49 - "Community 49"
Cohesion: 1.0
Nodes (2): getToken(), synthesize()

### Community 51 - "Community 51"
Cohesion: 1.0
Nodes (2): buildKiroPayload(), convertMessages()

### Community 52 - "Community 52"
Cohesion: 1.0
Nodes (2): buildKiroPayload(), convertMessages()

### Community 57 - "Community 57"
Cohesion: 0.67
Nodes (1): Footer()

### Community 58 - "Community 58"
Cohesion: 1.0
Nodes (2): getRedirectUri(), GitLabAuthModal()

## Knowledge Gaps
- **Thin community `Community 26`** (8 nodes): `IFlowExecutor`, `.buildHeaders()`, `.buildUrl()`, `.constructor()`, `.createIFlowSignature()`, `.generateUUID()`, `.transformRequest()`, `iflow.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 27`** (7 nodes): `qoder.js`, `QoderExecutor`, `.buildHeaders()`, `.buildUrl()`, `.constructor()`, `.createSignature()`, `.transformRequest()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 31`** (6 nodes): `AzureExecutor`, `.buildHeaders()`, `.buildUrl()`, `.constructor()`, `.transformRequest()`, `azure.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 36`** (5 nodes): `opencode.js`, `OpenCodeExecutor`, `.buildHeaders()`, `.buildUrl()`, `.constructor()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 42`** (4 nodes): `ComboDetailPage()`, `getListingHref()`, `parseModelEntry()`, `page.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 49`** (3 nodes): `getToken()`, `synthesize()`, `googleTts.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 51`** (3 nodes): `openai-to-kiro.js`, `buildKiroPayload()`, `convertMessages()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 52`** (3 nodes): `openai-to-kiro.old.js`, `buildKiroPayload()`, `convertMessages()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 57`** (3 nodes): `Footer()`, `Footer.js`, `Footer.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 58`** (3 nodes): `getRedirectUri()`, `GitLabAuthModal()`, `GitLabAuthModal.js`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `POST()` connect `Community 1` to `Community 0`, `Community 2`, `Community 3`, `Community 4`, `Community 5`, `Community 6`, `Community 7`, `Community 10`, `Community 15`, `Community 16`, `Community 17`, `Community 25`?**
  _High betweenness centrality (0.198) - this node is a cross-community bridge._
- **Why does `log()` connect `Community 2` to `Community 0`, `Community 1`, `Community 3`, `Community 4`, `Community 5`, `Community 6`, `Community 7`, `Community 8`, `Community 10`, `Community 11`, `Community 12`?**
  _High betweenness centrality (0.187) - this node is a cross-community bridge._
- **Why does `error()` connect `Community 3` to `Community 0`, `Community 1`, `Community 2`, `Community 6`, `Community 7`, `Community 8`, `Community 9`, `Community 11`, `Community 12`, `Community 13`, `Community 15`, `Community 17`, `Community 23`?**
  _High betweenness centrality (0.112) - this node is a cross-community bridge._
- **Are the 73 inferred relationships involving `POST()` (e.g. with `getSettings()` and `get()`) actually correct?**
  _`POST()` has 73 INFERRED edges - model-reasoned connections that need verification._
- **Are the 52 inferred relationships involving `GET()` (e.g. with `getMitmStatus()` and `getSettings()`) actually correct?**
  _`GET()` has 52 INFERRED edges - model-reasoned connections that need verification._
- **Are the 84 inferred relationships involving `log()` (e.g. with `handleForward()` and `handleForwardRaw()`) actually correct?**
  _`log()` has 84 INFERRED edges - model-reasoned connections that need verification._
- **Are the 32 inferred relationships involving `DELETE()` (e.g. with `deleteMachineData()` and `sessionLookup()`) actually correct?**
  _`DELETE()` has 32 INFERRED edges - model-reasoned connections that need verification._