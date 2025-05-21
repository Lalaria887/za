package com.mca.multitheading;

import java.io.DatainputStream;
import java.ioException;
 
 public class ReadInput
    public static void main(String)[] agrs) throws ioException {
        DatainputStream ds = new DatainputStream(system.in);
        system.out.printin("Enter Your name");
        String name = ds.readLine();
        system.out.printin(name);
