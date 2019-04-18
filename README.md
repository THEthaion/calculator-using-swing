# calculator-using-swing

int a,b,c;
char ch;
private void jButton1ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"1");
}
private void jButton2ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"2");
}
private void jButton3ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"3");
}
private void jButton4ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"4");
}
private void jButton5ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"5");
}
private void jButton6ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"6");
}
private void jButton7ActionPerformed(java.awt.event.ActionEvent evt)
{
jTextField1.setText(jTextField1.getText()+"7");
}
private void jButton8ActionPerformed(java.awt.event.ActionEvent evt) {
jTextField1.setText(jTextField1.getText()+"8");
}
private void jButton9ActionPerformed(java.awt.event.ActionEvent evt) {
jTextField1.setText(jTextField1.getText()+"9");
}
private void jButton10ActionPerformed(java.awt.event.ActionEvent evt) {
jTextField1.setText(jTextField1.getText()+"0");
}
private void jButton11ActionPerformed(java.awt.event.ActionEvent evt) {
a=Integer.parseInt(jTextField1.getText());
jTextField1.setText(jTextField1.getText()+"+");
jTextField2.setText(jTextField1.getText());
jTextField1.setText("");
ch='+';
}
private void jButton12ActionPerformed(java.awt.event.ActionEvent evt) {
a=Integer.parseInt(jTextField1.getText());
jTextField1.setText(jTextField1.getText()+"-");
jTextField2.setText(jTextField1.getText());
jTextField1.setText("");
ch='-';
}
private void jButton13ActionPerformed(java.awt.event.ActionEvent evt) {
a=Integer.parseInt(jTextField1.getText());
jTextField1.setText(jTextField1.getText()+"*");
jTextField2.setText(jTextField1.getText());
jTextField1.setText("");
ch='*';
}
private void jButton14ActionPerformed(java.awt.event.ActionEvent evt) {
a=Integer.parseInt(jTextField1.getText());
jTextField1.setText(jTextField1.getText()+"/");
jTextField2.setText(jTextField1.getText());
jTextField1.setText("");
ch='/';
}
private void jButton15ActionPerformed(java.awt.event.ActionEvent evt) {
b=Integer.parseInt(jTextField1.getText());
jTextField2.setText(jTextField2.getText()+jTextField1.getText());
jTextField1.setText("=");
switch(ch)
{
case '+':
c=a+b;
break;
case '-':
c=a-b;
break;
case '*':
c=a*b;
break;
case '/':
c=a/b;
break;
default:
jTextField1.setText("Invalid Choice");
}
jTextField1.setText(c+"");
}
