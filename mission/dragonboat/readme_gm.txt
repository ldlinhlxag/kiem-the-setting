?pl me.AddItem(18,1,326,1) --�������1
?pl me.AddItem(18,1,326,2) --�������2
?pl me.AddItem(18,1,326,3) --�������3
?pl me.AddItem(18,1,326,4) --�������4
?pl me.AddItem(18,1,327,1) --�������1
?pl me.AddItem(18,1,327,2) --�������2
?pl me.AddItem(18,1,327,3) --�������3
?pl me.AddItem(18,1,327,4) --�������4
?pl me.AddItem(22,1,63,1)  --�����ɼľ
?pl me.AddItem(22,1,64,1)  --�����ɼľ��
?pl me.AddItem(22,1,65,1)  --��ô�����
?pl me.AddItem(22,1,66,1)  --��ô�����
?pl me.AddItem(22,1,67,1)  --��ô�ͩ��
?pl me.AddItem(22,1,68,1)  --�����Ʒͩ��

?pl me.SetTask(2064, 15, 10) --���ô���
?pl me.SetTask(2064, 16, 10) --���ö������
?pl me.SetTask(2064, 17, 0) --ÿ�컻ȡ�����������¼����
?pl me.SetTask(2064, 18, 0) --ÿ�컻ȡ�����������¼ʱ��

?gc Esport:ScheduletaskDragonBoat()	--��������

--�������ٶ����˲��ܿ���
?gc Console:GetBase(Console.DEF_DRAGON_BOAT).tbCfg.nMinDynPlayer=1;
GlobalExcute{\"GM:DoCommand\",[[Console:GetBase(Console.DEF_DRAGON_BOAT).tbCfg.nMinDynPlayer=1]]}

--���ñ���ʱ�䣻
?gc Console:GetBase(Console.DEF_DRAGON_BOAT).tbCfg.nReadyTime=18*30;
GlobalExcute{\"GM:DoCommand\",[[Console:GetBase(Console.DEF_DRAGON_BOAT).tbCfg.nReadyTime=18*30]]}
