# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 7.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.539 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.228 ops/ms
Iteration   1: 13.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.091 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.957 ops/ms
Iteration   1: 13.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.513 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ops/ms
Iteration   1: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.480 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.077 ms/op
Iteration   1: 2.309 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.309 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.060 ms/op
Iteration   1: 2.193 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ±(99.9%) 0.061 ms/op
Iteration   1: 2.393 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.084 ms/op
Iteration   1: 3.190 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.190 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ±(99.9%) 0.098 ms/op
Iteration   1: 2.185 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   3.672 ms/op
                 createUser·p0.999:  19.235 ms/op
                 createUser·p0.9999: 20.285 ms/op
                 createUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14623
  mean =      2.185 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12136 
    [ 2.500,  5.000) = 2389 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.672 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     20.285 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ±(99.9%) 0.092 ms/op
Iteration   1: 1.699 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   1.591 ms/op
                 existUser·p0.90:   2.007 ms/op
                 existUser·p0.95:   2.195 ms/op
                 existUser·p0.99:   2.670 ms/op
                 existUser·p0.999:  12.986 ms/op
                 existUser·p0.9999: 13.827 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18808
  mean =      1.699 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 18281 
    [ 2.500,  3.750) = 149 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.591 ms/op
     p(90.0000) =      2.007 ms/op
     p(95.0000) =      2.195 ms/op
     p(99.0000) =      2.670 ms/op
     p(99.9000) =     12.986 ms/op
     p(99.9900) =     13.827 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ±(99.9%) 0.091 ms/op
Iteration   1: 1.836 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   1.714 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.478 ms/op
                 getUser·p0.99:   3.070 ms/op
                 getUser·p0.999:  13.641 ms/op
                 getUser·p0.9999: 14.004 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17473
  mean =      1.836 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 257 
    [ 1.250,  2.500) = 16425 
    [ 2.500,  3.750) = 679 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.070 ms/op
     p(99.9000) =     13.641 ms/op
     p(99.9900) =     14.004 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.111 ms/op
Iteration   1: 3.330 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.629 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.500 ms/op
                 listUser·p0.99:   7.558 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 15.417 ms/op
                 listUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9733
  mean =      3.330 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 1240 
    [ 2.500,  3.750) = 6001 
    [ 3.750,  5.000) = 2187 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.500 ms/op
     p(99.0000) =      7.558 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     15.417 ms/op
     p(99.9990) =     15.417 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.539          ops/ms
ClientSimple.existUser                       thrpt         13.091          ops/ms
ClientSimple.getUser                         thrpt         13.513          ops/ms
ClientSimple.listUser                        thrpt          8.480          ops/ms
ClientSimple.createUser                       avgt          2.309           ms/op
ClientSimple.existUser                        avgt          2.193           ms/op
ClientSimple.getUser                          avgt          2.393           ms/op
ClientSimple.listUser                         avgt          3.190           ms/op
ClientSimple.createUser                     sample  14623   2.185 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.992           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.672           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.235           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.285           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.906           ms/op
ClientSimple.existUser                      sample  18808   1.699 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.633           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.591           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.195           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.670           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.986           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.827           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.943           ms/op
ClientSimple.getUser                        sample  17473   1.836 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.070           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.641           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.004           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.041           ms/op
ClientSimple.listUser                       sample   9733   3.330 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.629           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.500           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.558           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.303           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.417           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.417           ms/op

Benchmark result is saved to 1715688984934.json
