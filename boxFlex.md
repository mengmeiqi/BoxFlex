#1.boxFlex:
    ���Ժ���ģ�͡����Ժ�ģ�͡����ԺС����Ժ��ӡ������С���������

#2.�Ƽ���վ��
    www.zhangxinxu.com ���Ժ���ģ��

#3.Ĭ�ϲ������У������ǵ��Եģ�����������ı仯���仯�����丸Ԫ�ص�ʣ��ռ䡣

#4.��Ŀǰ���ԣ���Firefox/Chrom/Safari�����֧�ֵ��Ժ���ģ�ͣ�ʹ��ʱ����ǰ׺��

#���Ժ�ģ��д����
#5. �ɷ���:
    ����Ԫ�ؼ�display:box;
        #main{
            display:-webkit-box;
            display:-moz-box;
            display:box;
        } //����Ԫ�ؼ�display
    ����Ԫ�ؼ�box-flex:
        #main div{
            height:300px;
            -webkit-box-flex:1;
            -moz-box-flex:1;
            box-flex:1;
        }

#6.�·�����
    ����Ԫ�ؼ�display:flex;
        #main{
            display:flex;
            display:-webkit-flex;
            display:-moz-flex;
        }
    ����Ԫ�ؼ�flex-grow:1;
        #main div{
            flex-grow:1;
            -webkit-flex-grow:1;
            -moz-flex-grow:1;
        }

#7.�¾ɵ��Ժ�ģ�Ͳ��
    (1)��ʹ�õ��Ժ�ģ�͵�ʱ��Ԫ�ر���Ҫ��display:box �� display:inline-box:
        �°浯�Ժ�ģ�ͣ�flex��display : flex
        �ϰ浯�Ժ�ģ�ͣ�box : display : -webkit-box
    (2)box-orient �����ģ�͵����᷽��
        �°棺flex��flex-direction: row / column
        �ϰ棺box : -webkit-box-orient:
    ??      horizontal ˮƽ��ʾ     vertical ��ֱ����??
    (3)box-direction Ԫ������˳��
        �°棺flex : flex-direction: row-reverse / column-reverse;
        �ϰ棺box : -webkit-box-direction:
              normal ����???reverse ����
    (4)box-pack ���᷽��ԣ�Ŀռ����
        �°棺flex : justify-content : flex-start / flex-end / center
              / space-between / space-around;
        �ϰ棺box : -webkit-box-pack
              start ������Ԫ���ں��������ʾ����ԣ�ռ����Ҳ�
              end ������Ԫ���ں����Ҳ���ʾ����ԣ�ռ�����
              center ������Ԫ�ؾ���
              justify ��ԣ�ռ�����Ԫ��֮��ƽ���ֲ�
    (5)box-align ���᷽����ԣ�Ŀռ����
        �°棺flex : align-items : flex-start / flex-end / center / baseline
        �ϰ棺box : -webkit-box-align
              star ������Ԫ���ھݶ�
              end ������Ԫ���ھݵ�
              center ������Ԫ�ؾ���
    (6)Box-flex ������ӵĵ��Կռ�
        �°棺flex : flex-grow
        �ϰ棺box : -webkit-box-flex
    (7)box-ordinal-group ����Ԫ�صľ���λ��
        �°棺flex : order
        �ϰ棺box : -webkit-box-ordinal-group

#8.ע�⣺�����Ԫ������������,���Ƚ�����ɱ�����
    <div id="main">
            <div id="left"><h1>This is 'Left'.</h1></div>
            <div id="center"><h1>This is 'center'.This is 'center'.</h1></div>
            <div id="right"><h1>This is 'right'.</h1></div>
    </div>
  �������������Ԫ�ؼӿ���width:0;
    #main div{
        width:0;
    }

#9.ʵ����
    (1)���в��֣����̶����Ҳ�����Ӧ
        ���� ����λ ������margin ;table ;���Ժ�ģ�� ��
    (2)���в��֣����ҹ̶����м�����Ӧ
        ���� ����λ �����Ժ�ģ�� ��
    (3)���в��֣����¹̶����м�����Ӧ
        ��λ �����Ժ�ģ�� ��