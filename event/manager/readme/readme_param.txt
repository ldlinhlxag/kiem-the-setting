�����ϵͳ��������Ĳ�����˵��
 
��������:
d       --����
dTsk    --�������(����)
s       --�ַ���

--�����¼�
Npc:d		--����:Npc:2601  (����ٶԻ�2601Ϊ���Id   )
Item:s,s,n,n	--����:Item:lingpai,1440,10,1 (��Ʒlingpai����,ʹ�ú�������Ʒ,lingpaiΪ��Ʒclassname,1440Ϊ��Ʒ��Ч��,10Ϊʹ����Ʒ����������ʱ��,1Ϊ�ɹ�ʹ����Ʒ���Ƿ�ɾ����Ʒ)
DropNpc:d	--����:DropNpc:1000 (IdΪ1000��npc����ʱ����)
DropNpcType:s	--����:DropNpcType:merchant (merchantΪnpc��classname,ĳ��npc����ʱ����)(�������ͣ�_JINGYING:��Ӣ��_SHOULING:���죬_ALLNPC:����npc)
TimerStart:d	--����:TimerStart:1015 10��15�ִ����¼���ʼ(��-1Ϊ�������������ϴ���)
TimerEnd:d	--����:TimerEnd:1015 10��15�ִ����¼�����

û�д����¼�,Ĭ��Ϊ�������������ϴ���


--����
CheckTask:dTsk,d,s		--����:CheckTask:51,5,"���5��" (51������������ڵ���5�򷵻���ʾ��Ϣ)
CheckTaskEq:dTsk,d,s		--����:CheckTask:51,1,"�Ѳμӹ�" (51�������������1�򷵻���ʾ��Ϣ)
CheckTaskDay:d,dTsk,dTsk,s	--����:CheckTaskDay:5,51,52,"ÿ��ֻ��5��" (51��¼�������,52������¼����,51��������>=5�򷵻���ʾ��Ϣ)
CheckLevel:d,s			--����:CheckLevel:60,"Ҫ�ﵽ60������" (�ȼ�δ�ﵽ60�򷵻���ʾ��Ϣ)
CheckFaction:d,s		--����:CheckFaction:1,"�������������ܲμ�" (����IdΪ1Ϊ����,�������Ƿ�������,��������򷵻���ʾ��Ϣ)
CheckCamp:d,s			--����:CheckCamp:1,"����������" (ͬ��)
CheckSex:d,s			--����:CheckSex:0,"�������������" (0Ϊ��,1ΪŮ,������Ҫ���򷵻���ʾ)
CheckMonthPay:d,s		--����:CheckMonthPay:100,"�����ۼƳ�ֵ�����100Ԫ" (�ж��ۼƳ�ֵ�Ƿ�ﵽ����)
CheckWeiWang:d,s		--����:CheckWeiWang:100,"�������������100��" (�жϽ��������Ƿ�ﵽ����)
CheckFreeBag:d,s		--����:CheckFreeBag:2,"������Ҫ2�񱳰��ռ�" (�жϱ����ռ��Ƿ�ﵽ����)
CheckExt:d,s			--����:CheckExt:1,"���Ѿ����������" (���ÿ���ۼƳ�ֵ��չ�����λ�Ƿ����ĳֵ,���ڷ���ʧ��,�����Ѽ���)
CheckWeek:d,s			--����:CheckWeek:1,"���ڲ�����1,���ܲμӻ" (���������ܼ����ܲμӻ, �ܱ�ʾ:0-6)
CheckItemInBag:d,d,d,d,d,d,s	--����:CheckItemInBag:18,1,1,1,2,0,"������û��2��1����" �� CheckItemInBag:18,1,1,1,2,1,"�������Ѿ���2��1����"
CheckItemInAll:d,d,d,d,d,d,s	--����:CheckItemInAll:18,1,1,1,2,0,"�����ϻ�ֿ�û��2��1����" �� CheckItemInAll:18,1,1,1,2,1,"�����ϻ�ֿ��Ѿ���2��1����"
CheckInMapType:s,d,s		--����:CheckInMapType:"fight",0,"������Ұ���ͼ" �� CheckInMapType:"fight",1,"���벻��Ұ���ͼ"
CheckInMapLevel:d,d,s		--����:CheckInMapLevel:50,0,"������50����50�����ϵ�ͼ" �� CheckInMapLevel:50,1,"������50����ͼ" �� CheckInMapLevel:50,2,"������50�����µĵ�ͼ"
CheckNpcAtNear:d,d,s		--����:CheckNpcAtNear:1000,1,"IDΪ1000�������ҵ�npc�����Ҹ���" �� CheckNpcAtNear:1000,0,"IDΪ1000��npc�����Ҹ���"
CheckDialogNpcAtNear:s		--����:CheckDialogNpcAtNear:"�ҵĸ����жԻ�npc��"


--ִ��
SetTask:dTsk,d			--����:SetTask:51,2 (51������������ó�2)
SetMsg:s			--����:SetMsg:s (����ִ����ɺ���ʾ�Ի�����(Dialog))
SetAwardId:d			--����:SetAwardId:1	(ִ�н������еĵ�1������)
SetAwardIdUi:d			--����:SetAwardIdUi:2	(�������ִ�н������еĵ�2������)
SetCallNpcId:d			--����:SetCallNpcId:1	(ִ���ٻ�npc���еĵ�һ������)
SetDropItemId:d,d		--����:SetDropItemId:1,10	(��������ʱ,ִ�е�����еĵ�һ������,����ִ�д���10��)
SetDroprate:s,d			--����:SetDroprate:"\setting\npc\droprate\droprate_10.txt",5	(��������ʱ,ִ��\setting\npc\droprate\droprate_10.txt�����,ִ�д���5��)
AddTask:dTsk,d			--����:AddTask:51,2 (51���������ֵ��2)
AddTaskDay:dTsk,dTsk		--����:AddTaskDay:51,52 (ִ��ÿ���ܲμӵĴ�����1,51�����������1,52�ű�����¼��)
AddItem:d,d,d,d,d,d,d		--����:AddItem:18,1,1,9,2,1,1440 (�����Ʒ,18,1,1,9Ϊ9��Id, 2Ϊ2��,1Ϊ��,1440Ϊ�����Ч��1440����)
AddTitle:d,d,d,d		--����:AddTitle:3,2,1,0 (��óƺ�,4������Ϊ�ƺ�Idֵ)
AddSkillBuff:d,d,d		--����:AddSkillBuff:892,1,1440 (���״̬,892Ϊ״̬����Id, 1Ϊ�ȼ�, 1440Ϊ��Ч��,��λ����)
AddExt:d			--����AddExt:1	(ÿ���ۼƳ�ֵ��չ�����λ��ֵ����1)

SetLayer1Msg:s			--����:SetLayer1Msg:"���˽�ʲô��"(���Ի�����һ������)
SetLayer2Msg:s,s		--����:SetLayer2Msg:"���ڻ","���ָ...."(���Ի����ڶ���ѡ�������);