����͔��F�̐F�E�o���s�����B����𗘗p���邱�Ƃɂ��A�J�����f������l�̔��̕������킩��₷��
�\���ł���悤�ɂȂ����B���F�̕����𔒁A����ȊO�̕��������ɕ\�����邱�Ƃɂ��A���ȊO�̉ӏ�
�ł���ڂ���Ȃǂ͍����\������邽�ߗ֊s�Ȃǂ��킩��₷���Ȃ��Ă���B����ɔ��F�̕��͂��܂�Ȃ��ƍl����ƁA
���̕����������\������邽�߁A��蔧�̕������킩��₷���Ȃ��Ă���B
����̓T�C�ghttps://algorithm.joho.info/programming/python/opencv-color-tracking-py/
���Q�l�ɂ����Ă�������B
�����̓J���[�ǐՂ���R�[�h�ł��邪�A���ꂾ�����Ɠ��ʂȗv�f���Ȃ��̂ŁA���F��E�o�ł���
�悤�ɂ��A���̔��F����ǂ��ɐl�����邩�Ȃǂ��킩��悤�ɂȂ�B

�R�[�h�̐���
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)�ɂ��A�摜��hsv�ϊ����Ă���
hsv_min = np.array([0,58,88])
hsv_max = np.array([30,255,255])����ɂ�蔧�F��E�o����悤�ɕϊ�����
cv2.imshow("camera", frame)
cv2.imshow("hadairo", mask)�����Ō��̉f���ƁA�ϊ���̔����摜��\�����Ă���
if cv2.waitKey(25) & 0xFF == ord('q'):q���������ƃE�B���h�E�����

���H����
https://www.youtube.com/watch?v=0JHKv62nxCo



