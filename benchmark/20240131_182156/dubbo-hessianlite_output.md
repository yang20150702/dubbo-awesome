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
# Warmup Iteration   1: 2.400 ops/ms
Iteration   1: 5.466 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.466 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.821 ops/ms
Iteration   1: 13.204 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.204 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ops/ms
Iteration   1: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.879 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
Iteration   1: 3.872 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.872 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ±(99.9%) 0.066 ms/op
Iteration   1: 3.260 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.260 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.151 ±(99.9%) 0.031 ms/op
Iteration   1: 1.896 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.896 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.050 ms/op
Iteration   1: 3.145 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.145 ms/op


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
# Warmup Iteration   1: 13.070 ±(99.9%) 0.207 ms/op
Iteration   1: 8.356 ±(99.9%) 0.098 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.356 ms/op


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.127 ms/op
Iteration   1: 3.030 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.589 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 10.653 ms/op
                 createUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10560
  mean =      3.030 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 443 
    [ 2.000,  3.000) = 6460 
    [ 3.000,  4.000) = 2613 
    [ 4.000,  5.000) = 575 
    [ 5.000,  6.000) = 182 
    [ 6.000,  7.000) = 116 
    [ 7.000,  8.000) = 106 
    [ 8.000,  9.000) = 28 
    [ 9.000, 10.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.589 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     10.653 ms/op
     p(99.9990) =     10.682 ms/op
     p(99.9999) =     10.682 ms/op
    p(100.0000) =     10.682 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ±(99.9%) 0.073 ms/op
Iteration   1: 1.883 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 7.776 ms/op
                 existUser·p1.00:   7.799 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16965
  mean =      1.883 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 93 
    [1.000, 1.500) = 3290 
    [1.500, 2.000) = 7938 
    [2.000, 2.500) = 4761 
    [2.500, 3.000) = 573 
    [3.000, 3.500) = 59 
    [3.500, 4.000) = 37 
    [4.000, 4.500) = 75 
    [4.500, 5.000) = 47 
    [5.000, 5.500) = 30 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.357 ms/op
     p(99.9900) =      7.776 ms/op
     p(99.9990) =      7.799 ms/op
     p(99.9999) =      7.799 ms/op
    p(100.0000) =      7.799 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.302 ±(99.9%) 0.106 ms/op
Iteration   1: 3.304 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.629 ms/op
                 getUser·p0.99:   6.190 ms/op
                 getUser·p0.999:  22.265 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9838
  mean =      3.304 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1626 
    [ 2.500,  5.000) = 7929 
    [ 5.000,  7.500) = 240 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.629 ms/op
     p(99.0000) =      6.190 ms/op
     p(99.9000) =     22.265 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 11.171 ±(99.9%) 0.447 ms/op
Iteration   1: 8.228 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   7.897 ms/op
                 listUser·p0.90:   10.600 ms/op
                 listUser·p0.95:   11.544 ms/op
                 listUser·p0.99:   15.881 ms/op
                 listUser·p0.999:  27.103 ms/op
                 listUser·p0.9999: 28.410 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3887
  mean =      8.228 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 67 
    [ 5.000,  7.500) = 1473 
    [ 7.500, 10.000) = 1766 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.445 ms/op
     p(50.0000) =      7.897 ms/op
     p(90.0000) =     10.600 ms/op
     p(95.0000) =     11.544 ms/op
     p(99.0000) =     15.881 ms/op
     p(99.9000) =     27.103 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.466          ops/ms
Client.existUser                       thrpt         13.204          ops/ms
Client.getUser                         thrpt          7.879          ops/ms
Client.listUser                        thrpt          3.872          ops/ms
Client.createUser                       avgt          3.260           ms/op
Client.existUser                        avgt          1.896           ms/op
Client.getUser                          avgt          3.145           ms/op
Client.listUser                         avgt          8.356           ms/op
Client.createUser                     sample  10560   3.030 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.895           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.990           ms/op
Client.createUser:createUser·p0.95    sample          4.669           ms/op
Client.createUser:createUser·p0.99    sample          7.589           ms/op
Client.createUser:createUser·p0.999   sample          9.863           ms/op
Client.createUser:createUser·p0.9999  sample         10.653           ms/op
Client.createUser:createUser·p1.00    sample         10.682           ms/op
Client.existUser                      sample  16965   1.883 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.604           ms/op
Client.existUser:existUser·p0.50      sample          1.829           ms/op
Client.existUser:existUser·p0.90      sample          2.335           ms/op
Client.existUser:existUser·p0.95      sample          2.515           ms/op
Client.existUser:existUser·p0.99      sample          4.350           ms/op
Client.existUser:existUser·p0.999     sample          6.357           ms/op
Client.existUser:existUser·p0.9999    sample          7.776           ms/op
Client.existUser:existUser·p1.00      sample          7.799           ms/op
Client.getUser                        sample   9838   3.304 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample          0.998           ms/op
Client.getUser:getUser·p0.50          sample          3.219           ms/op
Client.getUser:getUser·p0.90          sample          4.096           ms/op
Client.getUser:getUser·p0.95          sample          4.629           ms/op
Client.getUser:getUser·p0.99          sample          6.190           ms/op
Client.getUser:getUser·p0.999         sample         22.265           ms/op
Client.getUser:getUser·p0.9999        sample         24.117           ms/op
Client.getUser:getUser·p1.00          sample         24.117           ms/op
Client.listUser                       sample   3887   8.228 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.445           ms/op
Client.listUser:listUser·p0.50        sample          7.897           ms/op
Client.listUser:listUser·p0.90        sample         10.600           ms/op
Client.listUser:listUser·p0.95        sample         11.544           ms/op
Client.listUser:listUser·p0.99        sample         15.881           ms/op
Client.listUser:listUser·p0.999       sample         27.103           ms/op
Client.listUser:listUser·p0.9999      sample         28.410           ms/op
Client.listUser:listUser·p1.00        sample         28.410           ms/op
