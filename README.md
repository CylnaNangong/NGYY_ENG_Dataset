English dataset of DiffSinger voicebank Nangong Yan & Yu / DiffSinger虚拟歌手 『南宫颜·羽』英语数据集


3. The dataset contains about 50 mins of English singing voice wav files with three different voice color from the same person, recorded with a condenser microphone in a quiet home environment.
4. Lable is in the cvs file.
1. Accoustic-related data is labelled with human correction after auto-labelling and in ARPAbetPlus way (with ax, dx, dr and tr) which is compatible with DIFF EN+ phonemizer.
2. There is ph_num and pitch-related information in the transcription file. However the pitch MIDI was automatically labelled by SOME and the speaker has poor pitch accuracy. This should be considered when training with auto-pitch model.
4. All the wav files are without any after-proccess except for slicing and clipping. You may process it as you want when you use it, e.g. de-noise, de-reverb.
5. The speaker is a non-native. This might lead to inconsistency in rhoticity and accents (American/British/...). However, it should still be mostly clear and understandable.
6. Republishing the data under the name of other person/virtual character is NOT ALLOWED.
7. Publishing any model trained with this data which reflects the traits of the original samples or generated contents from the kind of model mentioned above under the name of other person/virtual character is NOT ALLOWED.
8. It would be great and welcomed if you can credit "Nangong Yan & Yu" (『南宫颜·羽』) when you use the dataset in training and so. XD (the name of the virtual singer, NOT the owner of the respository)
9. The dataset might be updated in the future.


1. 本数据集含有共约时长50分钟、三个音色的英文演唱录音。音频使用电容麦在安静的家庭环境下录制。
2. 声学相关的标记已在自动标记后手动精修。音素方案为ARPAbetPlus（含有ax dx dr和tr）
3. 音高相关标记为~~SOME~~GAME自动标记。~~很抽象。小心使用。~~ 不知道现在还抽不抽象，但还请小心使用。
4. 音频没有经过任何除了剪辑以外的后期处理。使用时可自行处理。
5. 数据采集自非母语的英语使用者。发音习惯和口音可能会有前后不一致的状况。（但是应该还是能听懂的XD）
6. 不允许以他人或其他角色的名义二次发布该数据集。
7. 不允许以他人或其他角色的名义发布使用该数据集训练并可反映原采样特征的模型或该种模型产生的内容。
8. 如果在训练或其他情况下使用本数据集的时候能credit一下『南宫颜·羽』的话，~~我~~小颜小羽会很开心的XD
9. 本数据集日后可能会继续更新。
