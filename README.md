# AutoShaderScript_MayaEdu
This script is for artists who personally use Maya like Education or Indie version with V-Ray and Substance Painter. It will help you many setup of shaders automatically.
> �� ��ũ��Ʈ�� V-Ray�� ���꽺�Ͻ� �����Ϳ� �Բ� ���� ������ �̳� �ε������ ���������� ����ϴ� ��Ƽ��Ʈ�� ���� ���Դϴ�. ��ũ��Ʈ�� �����п��� �ڵ����� ���� ���̴� �¾��� ������ ���Դϴ�.

## Installation
1. Put three scripts(vrayDispSetting, ShaderMain.py, ShaderSetup.py) into a Maya scripts directory.
> 3���� ��ũ��Ʈ(vrayDispSetting, ShaderMain.py, ShaderSetup.py)�� ���� ��ũ��Ʈ ���丮�� �־��ּ���.
* Windows: C:\Users\{user_directory}\Documents\maya\scripts
2. Write these commands on Script Editor or Shelf Editor of Maya.
> ������ ��ũ��Ʈ �����Ϳ� ���� �����Ϳ� �� ��ɾ���� �ۼ����ּ���.
'''
import ShaderMain
reload(ShaderMain)
ShaderMain.MainWindow()
'''