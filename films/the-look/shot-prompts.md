# The Look — Shot Prompt Pack / 《那一眼》逐镜头生成提示词包

**Version:** 1.0  
**Status:** Generate only after character and location references are approved / 人物与场景参考获批后方可正式生成  
**Frame:** 16:9 horizontal, photorealistic live-action historical drama / 16:9横向，真人写实历史剧情片

## A. Global prompt header / 全局提示词头

**EN:** Photorealistic live-action historical drama set in first-century Judea, natural human anatomy and skin texture, historically plausible woven linen and wool garments, practical oil-lamp or firelight, restrained cinematic realism, muted earth and limestone palette, natural shadow falloff, 16:9 horizontal composition. Preserve exact approved identity, face, apparent age, hair, beard, costume and body proportions from supplied character references. Preserve approved location geometry, fire position, doorway position and screen direction. Natural understated acting, no theatrical posing.

**中文：** 第一世纪犹太地区背景的真人写实历史剧情片，自然人体结构与皮肤质感，符合时代的亚麻和羊毛织物，真实油灯或火光，克制的电影写实风格，低饱和大地色与石灰岩色彩，自然阴影衰减，16:9横向构图。严格保持已批准人物参考中的身份、面孔、年龄观感、头发、胡须、服装和身体比例。严格保持已批准场景中的空间结构、火堆位置、门洞位置与屏幕方向。表演自然克制，不摆戏剧化姿势。

## B. Global negative prompt / 全局排除项

**EN:** No halo, glowing eyes, supernatural beams, fantasy armor, medieval European styling, modern objects, synthetic-looking fabric, ornate jewelry, bags or backpacks, modern footwear, extra fingers, distorted hands, duplicated faces, identity drift, face beautification, plastic skin, exaggerated crying, theatrical anger, text, watermark, logos, frame borders, collage, split screen or horizontal mirroring.

**中文：** 不要光环、发光眼睛、超自然光束、奇幻盔甲、欧洲中世纪造型、现代物件、合成面料质感、华丽首饰、包袋或背包、现代鞋履；不要多余手指、畸形手部、重复面孔、人物身份漂移、过度美颜、塑料皮肤、夸张哭泣、戏剧化愤怒；不要文字、水印、标志、边框、拼贴、分屏或水平镜像。

## C. Identity lock / 人物身份锁定

Only use after the corresponding face reference is approved. / 对应人物面孔获批后才使用。

- PETER: approved Peter reference; adult first-century Galilean Jewish man; dark textured hair, ordinary beard, muted earth-tone tunic and outer garment.
- JESUS: approved Jesus reference; adult first-century Jewish man; dark hair and beard, simple undyed/light earth-tone tunic and outer garment.
- SERVANT WOMAN: approved reference; adult local woman, modest practical period clothing.
- FIRST MAN / SECOND MAN: two distinct approved adult male references; ordinary local clothing, no villain styling.

- 彼得：已批准的彼得参考图；第一世纪加利利犹太成年男性；深色有纹理头发、普通胡须、低饱和大地色长袍与外衣。
- 耶稣：已批准的耶稣参考图；第一世纪犹太成年男性；深色头发和胡须、朴素未染色／浅大地色长袍与外衣。
- 女仆：已批准参考图；当地成年女性，朴素实用的时代服装。
- 第一名男子／第二名男子：两张彼此有区别的已批准成年男性参考图；普通当地服装，不采用反派造型。

## D. Shot prompts / 逐镜头提示词

Every prompt below inherits the global header, negative prompt and approved identity/location references. / 以下每条提示词均继承全局提示词头、排除项及已批准人物／场景参考。

| ID / 镜头 | Duration / 时长 | English generation prompt | 中文生成提示词 |
|---|---:|---|---|
| TL-001 | 5s | Locked eye-level medium-wide inside a modest first-century upper room at night. Jesus and Peter sit facing one another across a low table. One practical oil lamp creates warm light and natural falloff. Other disciples are soft indistinct background figures. Quiet intimacy. | 夜晚朴素楼上房间，中远景平视固定机位。耶稣与彼得隔着矮桌相对而坐。一盏真实油灯形成温暖光线并自然衰减。其他门徒仅为虚化背景轮廓。氛围安静亲密。 |
| TL-002 | 5s | Medium close-up of Peter leaning slightly toward Jesus, speaking with sincere conviction. Direct open eyes, no arrogance or heroic posture. Almost imperceptible slow push-in. Match TL-001 lighting and room. | 彼得中近景，身体微微前倾，以真诚确信的状态说话。目光直接坦率，不傲慢、不摆英雄姿态。摄影机几乎难以察觉地缓慢推进。灯光和房间与TL-001一致。 |
| TL-003 | 8s | Stable close shot of Jesus speaking calmly, then a clean reaction on Peter receiving the prediction. No scolding or dramatic gesture. Peter listens, unable to imagine it coming true. | 耶稣稳定特写，平静说出预言，随后干净切换到彼得听见这句话的反应。没有责备或戏剧化动作。彼得认真听着，却无法想象预言会成真。 |
| TL-004 | 4s | Static wide night exterior of a compact stone courtyard, one modest fire deeper inside, dark passage opening visible. Cool-neutral night ambience and restrained warm fire accent. | 夜晚紧凑石砌院落的固定广角外景，深处有一处不大的火堆，可见黑暗通道。夜间环境冷中性，火光只是克制的暖色点缀。 |
| TL-005 | 5s | Locked wide master using the approved courtyard layout. Fire center-left foreground/midground, entry passage rear-left, a few ordinary people gathered. Peter enters from the passage side. Clear uncluttered geography. | 按已批准院落布局拍摄固定全景。火堆位于中前景偏左，入口通道位于后方偏左，少数普通人围坐。彼得从通道一侧进入。空间清晰、画面简洁。 |
| TL-006 | 4s | Medium two-shot by the fire. Peter settles at the edge of the group, avoiding attention. The servant woman notices him with a small head turn, not a dramatic reaction. Natural fire flicker. | 火堆旁中景双人镜头。彼得在群体边缘坐下，尽量不引人注意。女仆只轻微转头注意到他，不做夸张反应。火光自然变化。 |
| TL-007 | 3s | Over-Peter's-shoulder medium close-up of the servant woman looking toward him and speaking matter-of-factly. Observant, not hostile. Match shoulder and fire positions to master. | 过彼得肩中近景。女仆看向彼得，以平实语气说话。她是在观察，不带敌意。彼得肩部与火堆位置符合主镜头。 |
| TL-008 | 4s | Close-up of Peter answering quickly, “I do not know him.” One involuntary glance toward the passage betrays anxiety, then he looks back. Firelight on one side of his face, natural shadow on the other. | 彼得特写，快速回答“我不认识他”。一个不自觉的眼神瞥向通道，泄露焦虑，随后看回对方。火光照亮半边脸，另一侧自然落入阴影。 |
| TL-009 | 4s | Medium shot of the first man noticing Peter among the group. He speaks as if making an observation, without aggression. Background figures shift subtly but do not crowd Peter. | 第一名男子中景。他在人群中注意到彼得，以陈述事实般的语气开口，没有攻击性。背景人物轻微自然移动，不围逼彼得。 |
| TL-010 | 3s | Medium close-up of Peter replying briefly, “I am not.” Jaw tightens; tone more defensive than before. No extra gestures or explanatory words. | 彼得中近景，简短回答“我不是”。下颌略微绷紧，语气比第一次更具防御性。不要添加多余动作或解释性台词。 |
| TL-011 | 5s | Over-shoulder from the second man's side as he steps slightly closer and insists Peter was with Jesus, noting he is a Galilean. Begin after a subtle visual time ellipsis of about one hour: the fire is lower and background people have shifted slightly, while Peter remains in the same place. Keep fire and passage geography fixed. Certain, not threatening. | 从第二名男子一侧拍摄过肩镜头。他略微走近，坚持彼得曾与耶稣在一起，并指出他也是加利利人。用轻微视觉时间跳跃暗示约一小时过去：火势减弱，背景人物位置略有变化，但彼得仍在原处。火堆与通道的空间位置固定。语气肯定但不威胁。 |
| TL-012 | 8s | Tight close-up of Peter urgently denying he knows what the man is talking about. Fear breaks through his defensive tone. Too forceful, then caught in the last breath of the sentence. No theatrical shouting. | 彼得紧特写，急切否认自己知道对方在说什么。恐惧冲破防御性语气。他说得过于用力，随后停留在最后一口气上。不要戏剧化大喊。 |
| TL-013 | 6s | Locked close-up of Peter as the final syllable is still leaving his mouth. A natural off-screen rooster crow overlaps his speech. His body stops; his face changes after the sound begins. No bird cutaway, music sting or flash. | 彼得固定特写，最后一个音节尚未完全离开嘴边时，真实自然的画外鸡鸣响起，与说话重叠。彼得身体先停住，声音响起后脸部才变化。不切公鸡、不加音乐惊吓点或闪白。 |
| TL-014 | 4s | Medium-wide lateral shot of Jesus being escorted across the far side of the same courtyard, behind the fire group. Restrained plausible movement. Preserve approved face, costume, escort spacing and axis. This is cinematic staging, not a claim about Luke's exact blocking. | 中远景横向镜头。耶稣被押着从同一院落远侧、火堆人群后方经过。动作克制可信。保持已批准面孔、服装、押送者间距与轴线。这是电影调度，不代表路加记载了精确走位。 |
| TL-015 | 4s | Close/medium close-up of Jesus making a small clear turn of head and upper body toward Peter's established screen direction. Restrained human expression, emotionally open. No accusation gesture or supernatural effect. | 耶稣近景或中近景，头部与上半身朝彼得既定屏幕方向做出小而清晰的转动。表情克制真实，保留解释空间。不做指责手势或超自然效果。 |
| TL-016 | 4s | Close-up of Peter slowly lifting his eyes toward Jesus. Small movement; recognition before tears. Static camera. Match exact eyeline and light direction. | 彼得特写，缓慢抬眼看向耶稣。动作很小，先意识到真相，再出现泪水。摄影机静止，严格匹配视线和光线方向。 |
| TL-017 | 4s | Stable matched-eyeline composition or clean shot/reverse-shot pair. Jesus and Peter hold eye contact for four uninterrupted seconds. Direct and quiet, not angry, theatrical, sentimental or supernatural. Thin ambience slightly; no voice-over, music swell or slow motion. | 稳定匹配视线构图或干净正反打。耶稣与彼得保持四秒不间断对视。目光直接安静，不愤怒、不戏剧化、不煽情、不超自然。环境声略微降低；不加旁白、音乐渐强或慢动作。 |
| TL-018 | 4s | Tight close-up of Peter lowering his eyes. Tears gather slowly; no full breakdown yet. Recognition, then shame, then grief. Subtle human breathing. | 彼得紧特写，慢慢垂下目光。泪水逐渐聚集，此时还没有彻底崩溃。情绪顺序为意识、羞愧、悲痛。呼吸细微真实。 |
| TL-019 | 3s | Rear three-quarter medium shot as Peter turns away from the fire and walks into the established passage. He tries to maintain composure for the first steps. No prop, bag, stumble or theatrical gesture. | 后侧三分之二中景。彼得转离火堆，走进既定通道。最初几步仍努力维持镇定。不添加道具、包袋、踉跄或戏剧化动作。 |
| TL-020 | 3s | Locked shot of the fire and the space Peter has left. Others continue quiet ordinary activity; do not make everyone freeze. Let the empty place carry the ending. Cut to black, then show only Luke 22:62. | 固定镜头拍摄火堆与彼得离开后留下的空位。其他人仍保持普通、安静的活动，不要全体僵住。让空缺承载结尾。切黑后只显示路加福音22:62。 |

## E. Generation protocol / 生成流程

1. Never generate a character close-up before that character's approved face reference exists.
2. Generate a clean location master before close-ups; reuse it for every shot in that location.
3. Test TL-014–TL-017 as a continuity sequence first. Reject results that drift in identity or screen direction.
4. Prefer short controlled clips; generate handles where possible and trim in edit.
5. Never ask one generation to contain multiple cuts or several dialogue turns.
6. If lip-sync is unreliable, record dialogue separately and use reaction shots strategically.
7. Log tool/model/version, prompt version, aspect ratio, duration, references, seed if available, and defects for every take.

1. 没有已批准的人物面孔参考，不生成该人物特写。
2. 先生成干净的场景主参考，再生成近景；同一场景所有镜头复用该参考。
3. 优先把TL-014至TL-017作为连续性测试。人物身份或屏幕方向漂移的结果直接淘汰。
4. 优先生成短而可控的片段；工具支持时保留头尾余量，后期精剪。
5. 不要一次生成多个剪辑镜头或多轮对白。
6. 若口型同步不可靠，单独录制对白，并策略性使用反应镜头。
7. 每条素材记录工具／模型／版本、提示词版本、画幅、时长、参考资产、随机种子（如有）与瑕疵。
