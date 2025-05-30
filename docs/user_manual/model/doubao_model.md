## 1 添加模型

!!! Abstract ""
    选择模型供应商为`火山引擎`，并在模型添加对话框中输入如下必要信息：

    * 模型名称：GTAI 中自定义的模型名称。    
    * 权限：分为私有和公用两种权限，私有模型仅当前用户可用，公用模型即系统内所有用户均可使用，但其它用户不能编辑和删除。   
    * 模型类型：大语言模型/向量模型/语音识别/语音合成/视觉模型/图片生成。

!!! Abstract ""
    豆包大语言模型其它接入参数说明：

    * 基础模型：在线推理的接入点ID。        
    * API 域名：https://ark.cn-beijing.volces.com/api/v3
    * API Key：接入点-> API调用 -> 通过API Key授权 -> 选择 API Key 复制获取，如下图

![火山引擎 LLM模型](../../img/model/doubao_jieru.png)
![火山引擎 LLM模型](../../img/model/doubao_llm_apikey.png)


!!! Abstract "" 
    语音识别和语音合成需要输入App ID、Access Token、Cluster ID。

    * App 域名：语音识别模型 API 域名为`wss://openspeech.bytedance.com/api/v2/asr`，语音合成模型 API 域名为`wss://openspeech.bytedance.com/api/v1/tts/ws_binary`
    * App ID：在火山引擎中创建的应用ID。 
    * Access Token：在火山引擎应用对应的认证信息。 
    * Cluster ID：在火山引擎应用对应的服务信息.

![火山引擎_语音识别](../../img/model/doubao_stt.png)
![火山引擎o_语音合成](../../img/model/doubao_tts.png)

## 2 配置样例

!!! Abstract ""
    火山引擎-大语言模型配置样例图示如下：
![火山引擎 LLM模型](../../img/model/huoshan_llm.png){ width="500px" }

!!! Abstract ""
    火山引擎-向量模型配置样例图示如下：
![火山引擎 向量模型](../../img/model/huoshan_embedding.png){ width="500px" }

!!! Abstract ""
    火山引擎-语音识别模型配置样例图示如下：
![火山引擎 语音识别模型](../../img/model/huoshan_asr.png){ width="500px" }

!!! Abstract ""
    火山引擎-语音合成模型配置样例图示如下：
![火山引擎 语音合成模型](../../img/model/huoshan_tts.png){ width="500px" }

!!! Abstract ""
    火山引擎-视觉模型模型配置样例图示如下：
![火山引擎 视觉模型](../../img/model/doubao_vision.png){ width="500px" }

!!! Abstract ""
    火山引擎-图片生成模型需要在火山引擎【控制台-访问控制-API访问密钥】新建密钥，样例图示如下：
![火山引擎 图片生成](../../img/model/doubao_gen1.png){ width="500px" }

![火山引擎 图片生成](../../img/model/doubao_gen2.png){ width="500px" }

