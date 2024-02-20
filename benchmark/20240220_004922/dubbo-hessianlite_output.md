# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
Iteration   1: 5.417 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.417 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.690 ops/ms
Iteration   1: 11.711 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.711 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ops/ms
Iteration   1: 7.753 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.753 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.964 ops/ms
Iteration   1: 3.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.443 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.590 ±(99.9%) 0.075 ms/op
Iteration   1: 2.863 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.090 ±(99.9%) 0.033 ms/op
Iteration   1: 1.995 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.995 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ±(99.9%) 0.135 ms/op
Iteration   1: 3.011 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.011 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.656 ±(99.9%) 0.224 ms/op
Iteration   1: 8.350 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.266 ±(99.9%) 0.128 ms/op
Iteration   1: 3.744 ±(99.9%) 0.203 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.882 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   6.058 ms/op
                 createUser·p0.99:   16.105 ms/op
                 createUser·p0.999:  96.266 ms/op
                 createUser·p0.9999: 106.955 ms/op
                 createUser·p1.00:   106.955 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8550
  mean =      3.744 ±(99.9%) 0.203 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8302 
    [ 12.500,  25.000) = 203 
    [ 25.000,  37.500) = 12 
    [ 37.500,  50.000) = 1 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 6 
    [ 75.000,  87.500) = 9 
    [ 87.500, 100.000) = 12 
    [100.000, 112.500) = 5 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.882 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      6.058 ms/op
     p(99.0000) =     16.105 ms/op
     p(99.9000) =     96.266 ms/op
     p(99.9900) =    106.955 ms/op
     p(99.9990) =    106.955 ms/op
     p(99.9999) =    106.955 ms/op
    p(100.0000) =    106.955 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.109 ±(99.9%) 0.062 ms/op
Iteration   1: 2.113 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.105 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   3.219 ms/op
                 existUser·p0.999:  4.564 ms/op
                 existUser·p0.9999: 6.357 ms/op
                 existUser·p1.00:   6.447 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15264
  mean =      2.113 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 18 
    [1.000, 1.500) = 922 
    [1.500, 2.000) = 4788 
    [2.000, 2.500) = 7366 
    [2.500, 3.000) = 1867 
    [3.000, 3.500) = 234 
    [3.500, 4.000) = 31 
    [4.000, 4.500) = 23 
    [4.500, 5.000) = 7 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.219 ms/op
     p(99.9000) =      4.564 ms/op
     p(99.9900) =      6.357 ms/op
     p(99.9990) =      6.447 ms/op
     p(99.9999) =      6.447 ms/op
    p(100.0000) =      6.447 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.132 ms/op
Iteration   1: 3.385 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  9.610 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9466
  mean =      3.385 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1075 
    [ 2.500,  3.750) = 5951 
    [ 3.750,  5.000) = 2146 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =      9.610 ms/op
     p(99.9900) =     12.648 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.040 ±(99.9%) 0.396 ms/op
Iteration   1: 8.072 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   7.684 ms/op
                 listUser·p0.90:   10.699 ms/op
                 listUser·p0.95:   11.530 ms/op
                 listUser·p0.99:   17.610 ms/op
                 listUser·p0.999:  20.115 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4144
  mean =      8.072 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 132 
    [ 5.000,  7.500) = 1776 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 537 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.236 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =     10.699 ms/op
     p(95.0000) =     11.530 ms/op
     p(99.0000) =     17.610 ms/op
     p(99.9000) =     20.115 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.417          ops/ms
Client.existUser                       thrpt          11.711          ops/ms
Client.getUser                         thrpt           7.753          ops/ms
Client.listUser                        thrpt           3.443          ops/ms
Client.createUser                       avgt           2.863           ms/op
Client.existUser                        avgt           1.995           ms/op
Client.getUser                          avgt           3.011           ms/op
Client.listUser                         avgt           8.350           ms/op
Client.createUser                     sample   8550    3.744 ± 0.203   ms/op
Client.createUser:createUser·p0.00    sample           0.935           ms/op
Client.createUser:createUser·p0.50    sample           2.882           ms/op
Client.createUser:createUser·p0.90    sample           4.375           ms/op
Client.createUser:createUser·p0.95    sample           6.058           ms/op
Client.createUser:createUser·p0.99    sample          16.105           ms/op
Client.createUser:createUser·p0.999   sample          96.266           ms/op
Client.createUser:createUser·p0.9999  sample         106.955           ms/op
Client.createUser:createUser·p1.00    sample         106.955           ms/op
Client.existUser                      sample  15264    2.113 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample           0.656           ms/op
Client.existUser:existUser·p0.50      sample           2.105           ms/op
Client.existUser:existUser·p0.90      sample           2.576           ms/op
Client.existUser:existUser·p0.95      sample           2.724           ms/op
Client.existUser:existUser·p0.99      sample           3.219           ms/op
Client.existUser:existUser·p0.999     sample           4.564           ms/op
Client.existUser:existUser·p0.9999    sample           6.357           ms/op
Client.existUser:existUser·p1.00      sample           6.447           ms/op
Client.getUser                        sample   9466    3.385 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample           0.660           ms/op
Client.getUser:getUser·p0.50          sample           3.318           ms/op
Client.getUser:getUser·p0.90          sample           4.194           ms/op
Client.getUser:getUser·p0.95          sample           4.563           ms/op
Client.getUser:getUser·p0.99          sample           6.701           ms/op
Client.getUser:getUser·p0.999         sample           9.610           ms/op
Client.getUser:getUser·p0.9999        sample          12.648           ms/op
Client.getUser:getUser·p1.00          sample          12.648           ms/op
Client.listUser                       sample   4144    8.072 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample           3.236           ms/op
Client.listUser:listUser·p0.50        sample           7.684           ms/op
Client.listUser:listUser·p0.90        sample          10.699           ms/op
Client.listUser:listUser·p0.95        sample          11.530           ms/op
Client.listUser:listUser·p0.99        sample          17.610           ms/op
Client.listUser:listUser·p0.999       sample          20.115           ms/op
Client.listUser:listUser·p0.9999      sample          20.873           ms/op
Client.listUser:listUser·p1.00        sample          20.873           ms/op
