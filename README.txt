InfoChip8 v0.1J�����[�X�m�[�g
Copyright (c) 2005 Jay's Factory

���͂��߂�

InfoChip8 v0.1J for Win32�́AWin32��œ��삷��CHIP-8�G�~�����[�^�ł��B
�����ŁA�ڐA�����������Ƃ������ł��B

���C���X�g�[�����@

(1) �A�[�J�C�uInfoChip801.zip��W�J����
(2) ���s�t�@�C��./InfoChip801/bin/InfoChip8.exe���A�K���ȏꏊ
�@�@�i��Fc:\cygwin\usr\local\bin�j�ɃR�s�[����
(3) ���ϐ�PATH�ɁA�R�s�[��i��Fc:\cygwin\usr\local\bin�j�ݒ肷��
�@�@[�R���g���[���p�l��] - [�V�X�e��] - [�ڍאݒ�] - [���ϐ�]

���N�����@

(1) �R�}���h���C������A�ȉ����^�C�v����

$ InfoChip8 [ROM�t�@�C�����i��FPong�j]

(2) �������́AROM�t�@�C�����A���s�t�@�C��InfoChip8.exe�ɁA�h���b�O�A��
    �h�h���b�v����

(3) �I�����@�́A[�~]���N���b�N����

��������@

�L�[�́A�ȉ��̂悤�Ƀ}�b�s���O����Ă���B

�I���W�i���@|1|2|3|C|�@�@�}�b�s���O�@|1|2|3|4|
�@�@�@�@�@�@|4|5|6|D|�@�@�@�@�@�@�@�@|Q|W|E|R|
�@�@�@�@�@�@|7|8|9|E|�@�@�@�@�@�@�@�@|A|S|D|F|
�@�@�@�@�@�@|A|0|B|F|�@�@�@�@�@�@�@�@|Z|X|C|V|

���d�l

��������
�@- ROM�t�@�C���i200H - F10H�j
�@- 16�i���t�H���g�iF10H - F60H�j

�����W�X�^
�@- �f�[�^���W�X�^�iV0 .. VF�j
�@- �A�h���X���W�X�^�iI�j
�@- �^�C�}�i�f�B���C�A�T�E���h�j
�@- �X�^�b�N�i16���[�h���A�X�^�b�N�|�C���^�j

���O���t�B�b�N�X
�@- �X�v���C�g�iCHIP-8���[�h�F8 x 1 .. 15�j
�@- �Փ˃t���O
�@- 16�i���t�H���g

�����߃Z�b�g
�@- CHIP-8���߁i����A�Z�p�A��������A�T�u���[�`���A�X�v���C�g�A���j

���L�[�{�[�h
�@- 16�i���L�[�{�[�h

���r���h���@

�\�[�X���A�o�C�i���𐶐����邽�߂ɂ́A�ȉ������s����B

������

(1) Cygwin���C���X�g�[�����ɁA�ȉ����`�F�b�N����

All + Devel + gcc: C, C++, Fortran compilers
All + Devel + gcc-mingw: Mingw32 support headers and libraries for GCC

(2) �ȉ��̃t�@�C�����_�E�����[�h���A�W�J����

DirectX for MinGW
http://www.libsdl.org/extras/win32/common/directx-devel.tar.gz

(3) �C���N���[�h�t�@�C���ƃ��C�u�����t�@�C�����R�s�[����

$ cp ./include/*.h /usr/i686-pc-mingw32/include
$ cp ./lib/*.a /usr/i686-pc-mingw32/lib

�����r���h

(4) �A�[�J�C�uInfoChip801.zip��W�J����
(5) �f�B���N�g��./InfoChip801/src/win32�Ɉړ�����

$ cd ./InfoChip801/src/win32

(6) ���r���h����

$ make clean
$ make

[EOF]
