# DungeonRush
![](screenshot.gif)
[English](README.md) | ��������
> ��̰������������Ϸ����C + SDLͼ�ο⡣
> �����ҵ�C��ҵ��ϣ����ϲ�� :)

*�����Ŀ�����Լ���д������ע�ͱȽ���*
## ����˵��

### v1.0-beta
- �޸�Bug
- ��� ���� / ��������Multiplayer / LAN��ģʽ

**ͨ������������ĺ�������ˣ�ɣ�**
*����Ҫ��ͬһ���������IPֱ������*

### v1.0-alpha

���η���

## �淨

### ����ģʽ

ʹ�� WASD ���ƶ���

�ռ�Ӣ����������ľ��ӣ����������ܹ���Ĺ�����ÿ���ؿ�����һ�����ӵ�Ŀ�곤�ȡ��������Ŀ�곤�ȣ����������һ�������¿�ʼ���кܶණ���������ĵȼ����е�������������ֵ���˺�ϵ��������������������ȡ�

### ����ģʽ
ʹ�� WASD �ͼ�ͷ���������������ƶ���

����ģʽ���о���������ֹ���ܹ�������ѵĹ�����

### ����

�����ǻ������������ǿ�����������ͬ�����Ӣ�ۿ���װ����ͬ�����������

*�����������һ���ܿ��~~��ʺ��~~���ӣ������������ʦ�ٻ�����������Χ�Ķ����ˡ�*

### Buff/Debuff

Buff/Debuff����һ��ӵ���������˹���ʱ�������Լ���ĳЩ������߶Ե��˵ļ��档

- �������Ա������ˣ����˽��޷��ƶ���
- ʥ�����Ը���һ�����ƣ������˺���ʹ���Debuff���ߡ�
- �󹭿������������е�Ӣ�۵Ĺ����˺���
- ���кܶࡣ

��Ȼ����Щ���������������Ը���ʩ��Debuff�� *���ͱ��緳�˵���Ţ�ֿ��Լ�������ƶ��ٶȣ�*


## ����

[Windows(64λ)](https://github.com/Rapiz1/DungeonRush/releases/download/v1.0-beta/DungeonRush-v1.0-beta-Windows-x86_64.zip)

[Windows(32λ)](https://github.com/Rapiz1/DungeonRush/releases/download/v1.0-beta/DungeonRush-v1.0-beta-Windows-i686.zip)

[Linux](https://github.com/Rapiz1/DungeonRush/releases/download/v1.0-beta/DungeonRush-v1.0-beta-linux.zip)

AppImage for Linux �������� Release ҳ�����ҵ���

*�����Ϸ֧��macOS������û��Mac����������*

��ִ���ļ���`dungeon_rush`

## ������ϵ
����Ŀ������ SDL �⡣
`SDL2, SDL2-image, SDL2-mixer, SDL2-net, SDL2-ttf`
### Arch
```
# pacman -S sdl2 sdl2_image sdl2_mixer sdl2_net sdl2_ttf --needed
```
### Debian

```
# apt install libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-net-dev libsdl2-ttf-dev
```

### openSUSE

```
# zypper in libSDL2-devel libSDL2_image-devel libSDL2_mixer-devel libSDL2_net-devel libSDL2_ttf-devel
```

### MacOS

```
#  brew install sdl2 sdl2_image sdl2_mixer sdl2_net sdl2_ttf
```

### ����ϵͳ

������Ų�ࡣ�����Բ��� SDL �̳������û�����
## Compilation
**��Ӧ��ȷ���ڱ���֮ǰ��װ������������**
```
$ cmake -B build && cmake --build build
```
## ��֪����
[��һЩװ��NVIDIA����Linuxϵͳ�ϣ�����Ϸ�ٶ�̫��](https://github.com/Rapiz1/DungeonRush/issues/4)
## ��Ȩ�����
DungeonRush �Ѿ��Ѹ������֤��ý�������һ�𡣲��ҵ�����û�ҵ����ǡ����仰˵������಻�����������ڵ�δ֪���֤���㲻���������Ŀ���ظ�ʹ���κ���Ƶ��λͼ�����塣�������ʹ�ã������Ը���
### ����
GPL
### λͼ
|����|��ȨЭ��|
|----|--------|
|���� 0x72 �� DungeonTilesetII_v1.3|CC 0|
|�������� rapiz ��λͼ|CC BY-NC-SA 4.0|
### ��Ƶ
|����|��ȨЭ��|
|----|--------|
|���� Starbox �� Digital_Dream_Azureflux_Remix|CC BY-NC-SA 4.0|
|���� Azureflux �� BOMB|CC BY-NC-SA 4.0|
|δ֪��Ƶ|δ֪|
|���� Juhani Junkala �� The Essential Retro Video Game Sound Effects Collection|CC BY 3.0|
### ����
|����|��ȨЭ��|
|----|--------|
|Unifont|GPLv2|