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
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 5.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.891 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.914 ops/ms
Iteration   1: 14.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.207 ops/ms


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
# Warmup Iteration   1: 5.119 ops/ms
Iteration   1: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.678 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ops/ms
Iteration   1: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.512 ops/ms


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.069 ms/op
Iteration   1: 2.241 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.049 ms/op
Iteration   1: 2.222 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.081 ms/op
Iteration   1: 1.937 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.937 ms/op


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.085 ms/op
Iteration   1: 3.589 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.589 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.088 ms/op
Iteration   1: 2.127 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.418 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15037
  mean =      2.127 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11888 
    [ 2.500,  5.000) = 2927 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.070 ms/op
Iteration   1: 1.754 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.579 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.433 ms/op
                 existUser·p0.99:   3.269 ms/op
                 existUser·p0.999:  24.478 ms/op
                 existUser·p0.9999: 24.626 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18217
  mean =      1.754 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17458 
    [ 2.500,  5.000) = 693 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.579 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      3.269 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     24.626 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.090 ms/op
Iteration   1: 2.383 ±(99.9%) 0.138 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   1.976 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   4.708 ms/op
                 getUser·p0.999:  103.247 ms/op
                 getUser·p0.9999: 121.283 ms/op
                 getUser·p1.00:   121.373 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13428
  mean =      2.383 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13369 
    [ 12.500,  25.000) = 10 
    [ 25.000,  37.500) = 1 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 12 
    [ 62.500,  75.000) = 10 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 2 
    [100.000, 112.500) = 6 
    [112.500, 125.000) = 8 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.708 ms/op
     p(99.9000) =    103.247 ms/op
     p(99.9900) =    121.283 ms/op
     p(99.9990) =    121.373 ms/op
     p(99.9999) =    121.373 ms/op
    p(100.0000) =    121.373 ms/op


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
# Warmup Iteration   1: 5.683 ±(99.9%) 0.163 ms/op
Iteration   1: 3.469 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.646 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.088 ms/op
                 listUser·p0.9999: 12.665 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9231
  mean =      3.469 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 635 
    [ 2.500,  3.750) = 5698 
    [ 3.750,  5.000) = 2583 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     12.088 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           5.891          ops/ms
ClientSimple.existUser                       thrpt          14.207          ops/ms
ClientSimple.getUser                         thrpt          12.678          ops/ms
ClientSimple.listUser                        thrpt           8.512          ops/ms
ClientSimple.createUser                       avgt           2.241           ms/op
ClientSimple.existUser                        avgt           2.222           ms/op
ClientSimple.getUser                          avgt           1.937           ms/op
ClientSimple.listUser                         avgt           3.589           ms/op
ClientSimple.createUser                     sample  15037    2.127 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.418           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.177           ms/op
ClientSimple.createUser:createUser·p0.999   sample          21.627           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          21.856           ms/op
ClientSimple.createUser:createUser·p1.00    sample          21.856           ms/op
ClientSimple.existUser                      sample  18217    1.754 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.549           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.579           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.216           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.433           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.269           ms/op
ClientSimple.existUser:existUser·p0.999     sample          24.478           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          24.626           ms/op
ClientSimple.existUser:existUser·p1.00      sample          24.707           ms/op
ClientSimple.getUser                        sample  13428    2.383 ± 0.138   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.513           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.976           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.708           ms/op
ClientSimple.getUser:getUser·p0.999         sample         103.247           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         121.283           ms/op
ClientSimple.getUser:getUser·p1.00          sample         121.373           ms/op
ClientSimple.listUser                       sample   9231    3.469 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.646           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.971           ms/op
ClientSimple.listUser:listUser·p0.999       sample          12.088           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          12.665           ms/op
ClientSimple.listUser:listUser·p1.00        sample          12.665           ms/op

Benchmark result is saved to 1713573466620.json
