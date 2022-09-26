XML
MainActivity:
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".MainActivity"
 tools:layout_editor_absoluteY="81dp">
 <TextView
 android:id="@+id/textView"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="32dp"
 android:text="TextView"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent"
 tools:ignore="MissingConstraints" />
 <android.support.constraint.Guideline
 android:id="@+id/guideline"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:orientation="vertical"
 app:layout_constraintGuide_begin="20dp" />
 <Button
 android:id="@+id/button"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="54dp"
 android:text="Call"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/textView" />
 <Button
 android:id="@+id/button2"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="32dp"
 android:text="Dial call"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/button" />
 <Button
 android:id="@+id/button3"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="51dp"
 android:text="CallNumber"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/button2" />
 <Button
 android:id="@+id/button4"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="53dp"
 android:text="SMS"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/button3" />
 <Button
 android:id="@+id/button5"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginBottom="16dp"
 android:layout_marginTop="14dp"
 android:text="Mail"
 app:layout_constraintBottom_toBottomOf="parent"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/button4" />
</android.support.constraint.ConstraintLayout>
Call Number:
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".CallNumber">
 <EditText
 android:id="@+id/editText"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:layout_marginTop="24dp"
 android:ems="10"
 android:hint="Enter Phone Number"
 android:inputType="phone"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintHorizontal_bias="0.502"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent" />
 <Button
 android:id="@+id/button7"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="112dp"
 android:text="Call"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/editText" />
</android.support.constraint.ConstraintLayout>
Dial Call:
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout 
 xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".DialCall">
 <ImageButton
 android:id="@+id/imageButton"
 android:layout_width="90dp"
 android:layout_height="99dp"
 android:background="@drawable/ic_call_black_24dp"
 app:layout_constraintBottom_toBottomOf="parent"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>
SMS:
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".SMS">
 <EditText
 android:id="@+id/editText2"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:layout_marginTop="16dp"
 android:ems="10"
 android:hint="Phone Number"
 android:inputType="phone"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent" />
 <EditText
 android:id="@+id/editText3"
 android:layout_width="match_parent"
 android:layout_height="250dp"
 android:layout_marginTop="41dp"
 android:ems="10"
 android:gravity="left"
 android:inputType="textPersonName"
 android:hint="Type your SMS"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintHorizontal_bias="0.502"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/editText2" />
 <Button
 android:id="@+id/button6"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_marginTop="46dp"
 android:text="Send"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toBottomOf="@+id/editText3" />
</android.support.constraint.ConstraintLayout>
JAVA CODE:
MainActitity: 
public class MainActivity extends AppCompatActivity {
 Button button,button2,button3,button4,button5;
 private static final int REQUEST_CALL = 1;
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 button = findViewById(R.id.button);
 button2 = findViewById(R.id.button2);
 button3 = findViewById(R.id.button3);
 button4 = findViewById(R.id.button4);
 button5 = findViewById(R.id.button5);
 button.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 makecall();
 }
 });
 button2.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 startActivity(new 
Intent(MainActivity.this,DialCall.class));
 }
 });
 button3.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 startActivity(new 
Intent(MainActivity.this,CallNumber.class));
 }
 });
 button4.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 startActivity(new 
Intent(MainActivity.this,SMS.class));
 }
 });
 button5.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 startActivity(new 
Intent(MainActivity.this,Mail.class));
 }
 });
 }
 private void makecall() {
 if (ContextCompat.checkSelfPermission(MainActivity.this, 
Manifest.permission.CALL_PHONE)
 != PackageManager.PERMISSION_GRANTED) {
// 
ActivityCompat.requestPermissions(MainActivity.this,
// new 
String[]{Manifest.permission.CALL_PHONE}, REQUEST_CALL);
 
ActivityCompat.requestPermissions(MainActivity.this,new 
String[]{Manifest.permission.CALL_PHONE},REQUEST_CALL);
 } else {
 Intent o = new Intent(Intent.ACTION_CALL);
 o.setData(Uri.parse("tel:123"));
 startActivity(o);
 // startActivity(new Intent(Intent.ACTION_CALL, 
Uri.parse("tel:123")));
 }
 }
 @Override
 public void onRequestPermissionsResult(int requestCode, 
@NonNull String[] permissions, @NonNull int[] grantResults) {
 if (grantResults.length > 0 && grantResults[0] == 
PackageManager.PERMISSION_GRANTED) {
 makecall();
 } else {
 Toast.makeText(this, "Permission DENIED", 
Toast.LENGTH_SHORT).show();
 }
 }
}
Call Number
public class CallNumber extends AppCompatActivity {
 private static final int REQUEST_CALL=1;
 EditText editText;
 Button button;
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_call_number);
 editText = findViewById(R.id.editText);
 button = findViewById(R.id.button7);
 button.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 makeACall();
 }
 });
 }
 private void makeACall() {
 String number = editText.getText().toString();
 if (number.trim().length()>0){
 if 
(ContextCompat.checkSelfPermission(CallNumber.this,
 Manifest.permission.CALL_PHONE) != 
PackageManager.PERMISSION_GRANTED){
 
ActivityCompat.requestPermissions(CallNumber.this,
 new 
String[]{Manifest.permission.CALL_PHONE},REQUEST_CALL);
 }else {
 String call = "tel:" +number;
 Intent i = new Intent(Intent.ACTION_CALL);
 i.setData(Uri.parse(call));
 startActivity(i);
 //startActivity(new Intent(Intent.ACTION_CALL, 
Uri.parse(call)));
 }
 }else{
 Toast.makeText(CallNumber.this, "Enter Phone 
Number", Toast.LENGTH_SHORT).show();
 }
 }
 @Override
 public void onRequestPermissionsResult(int requestCode, 
@NonNull String[] permissions, @NonNull int[] grantResults) {
 if (requestCode == REQUEST_CALL){
 if (grantResults.length > 0 && grantResults[0] == 
PackageManager.PERMISSION_GRANTED) {
 makeACall();
 } else {
 Toast.makeText(this, "Permission DENIED", 
Toast.LENGTH_SHORT).show();
 }
 }
 }
}
Dial Call
public class DialCall extends AppCompatActivity {
 ImageButton imageButton;
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_dial_call);
 imageButton = findViewById(R.id.imageButton);
 imageButton.setOnClickListener(new 
View.OnClickListener() {
 @Override
 public void onClick(View v) {
 Intent i = new Intent(Intent.ACTION_DIAL);
 i.setData(Uri.parse("tel:123"));
 startActivity(i);
 }
 });
 }
}
SMS:
public class SMS extends AppCompatActivity {
 
 EditText editText,editText1;
 Button button;
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_sms);
 
 editText = findViewById(R.id.editText2);
 editText1 = findViewById(R.id.editText3);
 
 button = findViewById(R.id.button6);
 button.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View v) {
 sendSMS();
 }
 });
 }
 private void sendSMS() {
 String number1 = editText.getText().toString();
 String sms_ = editText1.getText().toString();
 if (number1.trim().length()>0){
 if (ContextCompat.checkSelfPermission(SMS.this, Manifest.permission.SEND_SMS)
 != PackageManager.PERMISSION_GRANTED){
 ActivityCompat.requestPermissions(SMS.this,
 new String[]{Manifest.permission.SEND_SMS},1);
 }else {
 try {
 SmsManager smsManager = SmsManager.getDefault();
 //smsManager.sendTextMessage(number1,null,sms_,null,null);
 smsManager.sendTextMessage(number1,null,sms_,null,null);
 Toast.makeText(SMS.this,"Sent",Toast.LENGTH_LONG).show();
 }catch (Exception e){
 Toast.makeText(SMS.this,"Failed",Toast.LENGTH_LONG).show();
 }
 }
 }else{
 Toast.makeText(SMS.this, "Enter Phone Number", Toast.LENGTH_SHORT).show();
 }
 }
 @Override
 public void onRequestPermissionsResult(int requestCode, @NonNull String[] permissions, 
@NonNull int[] grantResults) {
 if (requestCode == 1){
 if (grantResults.length > 0 && grantResults[0] == 
PackageManager.PERMISSION_GRANTED) {
 sendSMS();
 } else {
 Toast.makeText(this, "Permission DENIED", Toast.LENGTH_SHORT).show();
 }
 }
 }
}
