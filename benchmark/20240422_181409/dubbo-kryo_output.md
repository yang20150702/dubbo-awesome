# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.606 ops/ms
Iteration   1: 6.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.313 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.443 ops/ms
Iteration   1: 14.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.042 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.889 ops/ms
Iteration   1: 11.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.029 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ops/ms
Iteration   1: 7.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.782 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.078 ms/op
Iteration   1: 2.375 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.375 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ±(99.9%) 0.068 ms/op
Iteration   1: 1.834 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ±(99.9%) 0.060 ms/op
Iteration   1: 2.104 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.104 ms/op
Iteration   1: 3.208 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.208 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.500 ±(99.9%) 0.082 ms/op
Iteration   1: 2.100 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.548 ms/op
                 createUser·p0.95:   2.925 ms/op
                 createUser·p0.99:   8.526 ms/op
                 createUser·p0.999:  15.909 ms/op
                 createUser·p0.9999: 16.469 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15230
  mean =      2.100 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 13305 
    [ 2.500,  3.750) = 1288 
    [ 3.750,  5.000) = 243 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      8.526 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     16.469 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ±(99.9%) 0.072 ms/op
Iteration   1: 2.181 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.023 ms/op
                 existUser·p0.90:   2.661 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  25.935 ms/op
                 existUser·p0.9999: 26.955 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14632
  mean =      2.181 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12768 
    [ 2.500,  5.000) = 1668 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.661 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     25.935 ms/op
     p(99.9900) =     26.955 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ±(99.9%) 0.095 ms/op
Iteration   1: 2.791 ±(99.9%) 0.152 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.339 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   14.018 ms/op
                 getUser·p0.999:  99.118 ms/op
                 getUser·p0.9999: 103.674 ms/op
                 getUser·p1.00:   103.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 11469
  mean =      2.791 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 11351 
    [ 12.500,  25.000) = 44 
    [ 25.000,  37.500) = 36 
    [ 37.500,  50.000) = 6 
    [ 50.000,  62.500) = 3 
    [ 62.500,  75.000) = 7 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 6 
    [100.000, 112.500) = 11 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.339 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =     14.018 ms/op
     p(99.9000) =     99.118 ms/op
     p(99.9900) =    103.674 ms/op
     p(99.9990) =    103.809 ms/op
     p(99.9999) =    103.809 ms/op
    p(100.0000) =    103.809 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.161 ms/op
Iteration   1: 3.206 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  22.250 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9991
  mean =      3.206 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1884 
    [ 2.500,  5.000) = 7893 
    [ 5.000,  7.500) = 149 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     22.250 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.313          ops/ms
ClientSimple.existUser                       thrpt          14.042          ops/ms
ClientSimple.getUser                         thrpt          11.029          ops/ms
ClientSimple.listUser                        thrpt           7.782          ops/ms
ClientSimple.createUser                       avgt           2.375           ms/op
ClientSimple.existUser                        avgt           1.834           ms/op
ClientSimple.getUser                          avgt           2.104           ms/op
ClientSimple.listUser                         avgt           3.208           ms/op
ClientSimple.createUser                     sample  15230    2.100 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.786           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.548           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.925           ms/op
ClientSimple.createUser:createUser·p0.99    sample           8.526           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.909           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          16.469           ms/op
ClientSimple.createUser:createUser·p1.00    sample          16.581           ms/op
ClientSimple.existUser                      sample  14632    2.181 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.809           ms/op
ClientSimple.existUser:existUser·p0.50      sample           2.023           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.661           ms/op
ClientSimple.existUser:existUser·p0.95      sample           3.170           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.284           ms/op
ClientSimple.existUser:existUser·p0.999     sample          25.935           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          26.955           ms/op
ClientSimple.existUser:existUser·p1.00      sample          27.001           ms/op
ClientSimple.getUser                        sample  11469    2.791 ± 0.152   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.763           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.339           ms/op
ClientSimple.getUser:getUser·p0.90          sample           3.052           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.367           ms/op
ClientSimple.getUser:getUser·p0.99          sample          14.018           ms/op
ClientSimple.getUser:getUser·p0.999         sample          99.118           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         103.674           ms/op
ClientSimple.getUser:getUser·p1.00          sample         103.809           ms/op
ClientSimple.listUser                       sample   9991    3.206 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.030           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample          22.250           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientSimple.listUser:listUser·p1.00        sample          22.872           ms/op

Benchmark result is saved to 1713809397498.json
