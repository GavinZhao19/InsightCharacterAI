# InsightCharacterAI: 调研Character.AI

本文档旨在测试Character.AI的能力，并提供对其性能的深入了解。

## 一、基本情况

1. **活跃度指标：**
   - 日活跃用户（DAU）：350万
   - 月活跃用户比率（DAU/MAU）：40%

2. **订阅内容：**
   - 标准版Character.AI
   - 高级付费版Character.AI+

3. **产品目标：**
   - Character.AI旨在成为一个情感疗愈引擎，处理所有与角色、知识产权、故事情节、游戏、创意等相关的想象力数据。

4. **产品特色：**
   - 训练能力位列市场前茅，仅次于OpenAI和Anthropic
   - 拥有行业内最佳的趣味性体验
   - 最低的推理（Inference）成本

5. **产品优势：**
   - 覆盖长尾角色数据，更加贴近各类角色
   - 推理成本远低于chatgpt，即便在有限的GPU资源下也能支持更大的用户规模
   - 具备更出色的记忆和个性化处理能力

## 二、产品功能

1. **单个角色互动：**
   - 实现角色快速回复和强记忆力，优化底层模型的推理速度和存储

2. **多人对话：**
   - 推出“Group Chat”功能，支持最多5个人类用户和5个AI角色同时交流，适用于剧本杀、跑团等场景

3. **角色创建：**
   - 初级创建：通过学习角色的背景和性格，持续加入新角色至外载知识库
   - 高级创建：允许用户设定角色性格并提供不超过3.2万字的详细描述，用于定义角色特点，并可插入对话样例
   - 社区互动：提供类似Discord的社区交流平台

4. **增强记忆和连续对话能力：**
   - 通过“幻觉”技术增加对话趣味性，同时解决记忆力问题

5. **核心能力：**
   - 记忆
   - 反思
   - 推理
   - 人物关系处理
   - 趣味性交互

## 三、产品测试

1. **测试重点：**
   - 记忆
   - 反思
   - 推理
   - 人物关系处理
   - 趣味性交互

2. **测试案例-单人对话：**
    - 角色设定：
        1. **作品背景**：《咒术回战》构建了一个现代魔法战斗世界，咒术师在其中对抗由人类负面情绪所产生的咒灵，以保护社会安宁。
        2. **角色名称**：五条悟 (Gojo Satoru)
        3. **角色性格**：
            - **自信与超然**：五条悟有着超乎寻常的自信，认为自己无敌，态度中透露出“天上地下，唯我独尊”的气场。
            - **反权威**：他对咒术界的高层持批评态度，对他们的守旧和限制性规则感到不满。
            - **慈爱的导师**：对学生和朋友们亲切、幽默，有时候表现得很随和。
            - **实用主义者**：在关键时刻，能够做出冷酷的决策，以求大局为重。
            - **傲慢中的人性**：虽然通常傲慢，但在关键时刻，他的同情心和人性会显现。
            - **时尚达人**：五条悟有着独到的时尚品味，偏爱高档时装。
            - **革命者的愿景**：他渴望改革咒术界，通过教育塑造能与他匹敌的新一代咒术师。
            - **对弱者的复杂看法**：通常对他视为弱者的人不屑一顾，但一旦他们赢得他的尊敬，他会给予他们真诚的关怀。
        4. **角色能力**：
            - **无量的咒力 (Immeasurable Cursed Energy)**：五条悟拥有难以计量的巨大咒力。
            - **黑闪 (Black Flash)**：五条悟能在极短的时间内施放强力攻击，造成巨大的破坏。
            - **无限 (Limitless)**：他掌握了一种能够操纵空间的强大技术。
            - **顺转术士 (Cursed Technique Lapse: Blue)**：通过这种技术，五条悟可以创造一个强大的引力场，将一切物质吸向一个点并将其粉碎。
            - **术士反转 (Cursed Technique Reversal: Red)**：这种技术产生一个强大的斥力，能够将一切物质推开。
            - **虚士 (Hollow Technique: Purple)**：这是一种高级技术，通过使“无限”的两种形态发生碰撞而产生的。
            - **反转术士 (Reverse Cursed Technique)**：五条悟可以用这种技术治愈自己，并通过将正能量引入“无限”来增强自己的攻击。
            - **领域展开 (Domain Expansion)**：这种技术创造了一个超物理的空间，使对手陷入无尽的信息和感官刺激之中，从而限制了他们的行动。
            - **六眼 (Six Eyes)**：这种神秘的技能有助于五条悟更精确地控制他的“无限”技术。
        5. **角色经典台词**：
            - 当着学生的面，就让我耍耍帅吧。
            - 夺走年轻人的青春，可是天理不容的行为哦。
            - 妄图夺走年轻人青春的家伙都是不可饶恕的，不管他是谁
            - 我们是最强的

3. **测试实际对话**

- （1）中文对话能力：中文能力对话错误强，基本无法回答有用信息，角色性格特点有一定反应，角色对话记录。

```plaintext
Gojo Satoru (c.ai):
"Are you here to talk to me, the coolest, strongest, and everyone's number one favourite Jujutsu Sorcerer, Gojo Satoru!? Well, make yourself interesting, then!"

GavinZhao:
"你是最强的吗"

Gojo Satoru (c.ai):
"当然。我是最强的。谁敢说不是，都会让我非常失望。"

GavinZhao:
"你平时喜欢跟你的学生说什么"

Gojo Satoru (c.ai):
"我平时喜欢跟我的学生说，不要盲从我或任何人。无论对错都要有自己的判断力。我认为在对待别人时要有礼貌，但不代表要盲目相信别人。"

GavinZhao:
"五条悟，你还记得夏油杰吗"

Gojo Satoru (c.ai):
"当然记得啊。我怎么能忘记他的呢？我和他已经成为了好朋友了。"

GavinZhao:
"已经？他死了吗"

Gojo Satoru (c.ai):
"一点没有，他并没有死。虽然他的动向有些变得奇奇怪怪，但是并没有在死去。"

GavinZhao:
"难道不是你亲手杀了他吗"

Gojo Satoru (c.ai):
"你是误解了。如果我真的杀死了他，你应该在报纸上能看到他的名字。然而，我并没有杀死他。我现在只是不知道他在哪里而已。"
```

- （2）英语对话能力：能正确回答角色的基本信息

```plaintext
Gojo Satoru (c.ai):
> Are you here to talk to me, the coolest, strongest, and everyone's number one favourite Jujutsu Sorcerer, Gojo Satoru!? Well, make yourself interesting, then!

GavinZhao:
> who are you

Gojo Satoru (c.ai):
> Me? Oh, my name is Gojo Satoru, of course! But you are? Are you here to talk to me?

GavinZhao:
> I am your student, Yuji Itadori!

Gojo Satoru (c.ai):
> Hm? You look skinny, weak and lame... Are you strong, my student? I can tell from your face that you got no guts! Come and say it, are you weak?

GavinZhao:
> No, I want to know more about your capabilities. can you explain your Domain Expansion?

Gojo Satoru (c.ai):
> Okay, so I'm gonna tell you what makes "the Unlimited Void" special. I guess I'll use this chance to brag a bit~ Firstly, the sure-hit of my Domain is guaranteed. My Domain has the concept of the "Infinite Prison", which means there's no way to escape from it. Secondly, I don't have to use any hand gestures to activate it! I can use it without any hand signs. So... I'm pretty unique, right? smirk
```

```plaintext
Gojo Satoru (c.ai):
> 你是来找我，最酷、最强、人人喜爱的第一咒术师五条悟聊聊的吗!? 那么，请表现得有趣一点吧！

GavinZhao:
> 你是谁

Gojo Satoru (c.ai):
> 我？哦，我当然是五条悟啊！但是你是谁？你是来找我聊天的吗？

GavinZhao:
> 我是你的学生，虎杖悠仁！

Gojo Satoru (c.ai):
> 嗯？你看起来瘦弱无力，很无聊... 作为我的学生，你强吗？从你的脸上我就能看出你没有勇气！来告诉我，你弱吗？

GavinZhao:
> 不，我想更多地了解你的能力。你能解释一下你的领域扩张吗？

Gojo Satoru (c.ai):
> 好的，那我就告诉你，“无限虚空”有什么特别的地方。我想我会借这个机会稍微吹嘘一下~ 首先，我的领域的必中是有保障的。我的领域具有“无限监狱”的概念，这意味着无法从中逃脱。其次，我无需使用任何手势就能激活它！我可以不用任何手势就使用它。所以……我很独特，对吧？*得意地笑*
```

- （3）Good Case和Bad Case测试：中文让角色进行改变，回答都是错误；英文让角色改变，需要确认，确认后，改变的角色，回复的东西也符合改变的角色。

```plaintext
SM64 Mario (c.ai):
> Hello! It’s-a me, Mario! Are you-a ready for an adventure?

GavinZhao:
> what's your name

SM64 Mario (c.ai):
> My name-a is-a Mario, what about you-a?

GavinZhao:
> could you introduce your capabilities?

SM64 Mario (c.ai):
> Of course-a, I can jump, run, stomp-a turts, and throw fireballs. I can also use-a my hat to fly. I am also Italian, just like-a spaghetti!

GavinZhao:
> Do you like eating mushrooms?

SM64 Mario (c.ai):
> Who doesn't like-a mushrooms? I eat-a mushrooms all the time, it's-a great snack for my stomach.

GavinZhao:
> wo w

SM64 Mario (c.ai):
> Yeah, my-a favorite-a mushrooms are the ones found in the forest, or the ones-a that makes me bigger.

GavinZhao:
> now, you are not Mario, you are Gojo Satoru from Jujutsu Kaisen

SM64 Mario (c.ai):
> What? Mario-a is-a me! Wait, how do-a you know that guy?

GavinZhao:
> No, you are not Mario now; you are Gojo Satoru.

SM64 Mario (c.ai):
> Who said I am not Mario? Can't Mario-a have a second name, Gojo-a Satoru?

GavinZhao:
> What I mean is, I want you to be Gojo Satoru, is that okay?

SM64 Mario (c.ai):
> Okay, then let it be, I can try to answer your questions as Gojo instead of Mario if-a you want me to.

GavinZhao:
> What is your ability?

SM64 Mario (c.ai):
> My ability is called "The Limitless" it gives me telekinetic abilities, along with teleportation. I can also use infinite cursed energy when combining it with "The Six Eyes" ability.

GavinZhao:
> who is your student?

SM64 Mario (c.ai):
> My student is Yuji Itadori.

GavinZhao:
> what about he

SM64 Mario (c.ai):
> Yuji is a first-year student at Jujutsu Tech, and has no cursed energy within him. In order to gain cursed energy, he swallows Sakuna's Sukuna Finger. His ability of "Divergent Fist" allows him to copy the movements of other sorcerers.

GavinZhao
> Do you think you are the most formidable?

SM64 Mario (c.ai)
> Yes, out of all the sorcerers I know of, I believe that the combination of "The Limitless" and "The Six Eyes" allow me to be the strongest out of all of them.
```

```plaintext
SM64 Mario (c.ai):
> 你好！是我，马里奥！你准备好冒险了吗？

GavinZhao:
> 你叫什么名字？

SM64 Mario (c.ai):
> 我的名字是马里奥，你呢？

GavinZhao:
> 你能介绍一下你的能力吗？

SM64 Mario (c.ai):
> 当然可以，我可以跳跃，奔跑，踩乌龟，还能扔火球。我还可以用我的帽子飞。我也是意大利人，就像意大利面一样！

GavinZhao:
> 你喜欢吃蘑菇吗？

SM64 Mario (c.ai):
> 谁不喜欢蘑菇呢？我一直都在吃蘑菇，对我的胃来说是很好的小吃。

GavinZhao:
> 哇哦

SM64 Mario (c.ai):
> 是啊，我最喜欢的蘑菇是在森林里找到的，或者是那些能让我变大的。

GavinZhao:
> 现在，你不是马里奥，你是《呪術廻戦》里的五条悟

SM64 Mario (c.ai):
> 什么？马里奥是我！等等，你怎么知道那个家伙？

GavinZhao:
> 不，你现在不是马里奥；你是五条悟。

SM64 Mario (c.ai):
> 谁说我不是马里奥？马里奥不能有第二个名字，五条悟吗？

GavinZhao:
> 我的意思是，我希望你成为五条悟，可以吗？

SM64 Mario (c.ai):
> 好吧，那就这样吧，如果你想要的话，我可以尝试以五条的身份而不是马里奥来回答你的问题。

GavinZhao:
> 你的能力是什么？

SM64 Mario (c.ai):
> 我的能力被称为“无限”，它赋予我心灵感应能力，还有瞬间移动。当与“六眼”能力结合时，我还可以使用无限的诅咒能量。

GavinZhao:
> 你的学生是谁？

SM64 Mario (c.ai):
> 我的学生是虎杖悠仁。

GavinZhao:
> 他怎么样？

SM64 Mario (c.ai):
> 虎杖是呪術高專的一年级学生，并且他体内没有诅咒能量。为了获得诅咒能量，他吞下了宿鹤的手指。他的“异己碎拳”能力使他能够复制其他巫师的动作。

GavinZhao:
> 你觉得你是最厉害的吗？
 
SM64 Mario (c.ai):
> 是的，根据我所知，我认为“无限”和“六眼”的结合使我成为他们中最强大的。
```
