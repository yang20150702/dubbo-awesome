# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.702 ops/ms
Iteration   1: 6.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.854 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ops/ms
Iteration   1: 12.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.305 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ops/ms
Iteration   1: 12.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.185 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ops/ms
Iteration   1: 8.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.631 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.065 ms/op
Iteration   1: 2.064 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ±(99.9%) 0.043 ms/op
Iteration   1: 1.900 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.045 ±(99.9%) 0.055 ms/op
Iteration   1: 1.861 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.091 ms/op
Iteration   1: 3.602 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.602 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.091 ms/op
Iteration   1: 2.104 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   1.876 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.943 ms/op
                 createUser·p0.99:   7.860 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 28.353 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15428
  mean =      2.104 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13580 
    [ 2.500,  5.000) = 1643 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.943 ms/op
     p(99.0000) =      7.860 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     28.353 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.427 ±(99.9%) 0.119 ms/op
Iteration   1: 2.044 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.381 ms/op
                 existUser·p0.50:   1.931 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.814 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  16.482 ms/op
                 existUser·p0.9999: 16.614 ms/op
                 existUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15699
  mean =      2.044 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 515 
    [ 1.250,  2.500) = 13111 
    [ 2.500,  3.750) = 1850 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     16.614 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.090 ms/op
Iteration   1: 2.181 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  13.910 ms/op
                 getUser·p0.9999: 14.165 ms/op
                 getUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14662
  mean =      2.181 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 329 
    [ 1.250,  2.500) = 10385 
    [ 2.500,  3.750) = 3745 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     14.165 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.689 ±(99.9%) 0.145 ms/op
Iteration   1: 3.624 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8823
  mean =      3.624 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1016 
    [ 2.500,  3.750) = 4675 
    [ 3.750,  5.000) = 2710 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =     12.861 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.854          ops/ms
ClientSimple.existUser                       thrpt         12.305          ops/ms
ClientSimple.getUser                         thrpt         12.185          ops/ms
ClientSimple.listUser                        thrpt          8.631          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          1.861           ms/op
ClientSimple.listUser                         avgt          3.602           ms/op
ClientSimple.createUser                     sample  15428   2.104 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.490           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.876           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.943           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.860           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.822           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.353           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.869           ms/op
ClientSimple.existUser                      sample  15699   2.044 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.381           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.931           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.814           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.841           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.482           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.614           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.679           ms/op
ClientSimple.getUser                        sample  14662   2.181 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.549           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.571           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.910           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.165           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.287           ms/op
ClientSimple.listUser                       sample   8823   3.624 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.991           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.861           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.252           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.317           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.317           ms/op

Benchmark result is saved to 1722473245646.json
