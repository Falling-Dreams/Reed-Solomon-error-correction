# Reed-Solomon-error-correction
Reed–Solomon error correction in java, providing RS(255,233) encode and decode method.

----------
#Usage
encode the string before net transmission or local storage:
  

    RSEncoder encoder=new RSEncoder();
    byte[] bytes=encoder.encode(string);

decode while receiving from network or reading from the disk

    String result=decoder.decode(receive);
