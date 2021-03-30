
<?php
  //variable setting
  $name = $_REQUEST['name'];
  $email = $_REQUEST['email'];
  $subject = $_REQUEST['subject'];
  $message = $_REQUEST['message'];

  //check input fields
  if(empty($name) || empty($email) || empty($subject) ||empty($message))
  {
    echo ('Please fill all the fields.');
  }
  else{
    mail("john.doe@example.com", "Email Form", $message, "From: $name <$email>");
    echo "<script type='text/javascript'>alert('Your message sent successfully..!');
        window.history.go(-1);
    </script>";
  }
?>
