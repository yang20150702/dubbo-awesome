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
# Warmup Iteration   1: 1.585 ops/ms
Iteration   1: 6.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.754 ops/ms


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
# Warmup Iteration   1: 6.836 ops/ms
Iteration   1: 13.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.451 ops/ms


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
# Warmup Iteration   1: 6.418 ops/ms
Iteration   1: 12.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.845 ops/ms


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
# Warmup Iteration   1: 5.286 ops/ms
Iteration   1: 8.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.983 ops/ms


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.062 ms/op
Iteration   1: 2.038 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.038 ms/op


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
# Warmup Iteration   1: 2.967 ±(99.9%) 0.051 ms/op
Iteration   1: 1.959 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.959 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.044 ms/op
Iteration   1: 1.719 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.719 ms/op


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.118 ms/op
Iteration   1: 3.868 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.868 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.079 ms/op
Iteration   1: 1.957 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   1.868 ms/op
                 createUser·p0.90:   2.327 ms/op
                 createUser·p0.95:   2.488 ms/op
                 createUser·p0.99:   3.763 ms/op
                 createUser·p0.999:  23.047 ms/op
                 createUser·p0.9999: 25.121 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16332
  mean =      1.957 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15537 
    [ 2.500,  5.000) = 664 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.488 ms/op
     p(99.0000) =      3.763 ms/op
     p(99.9000) =     23.047 ms/op
     p(99.9900) =     25.121 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 2.846 ±(99.9%) 0.063 ms/op
Iteration   1: 2.065 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.040 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.706 ms/op
                 existUser·p0.99:   3.253 ms/op
                 existUser·p0.999:  6.177 ms/op
                 existUser·p0.9999: 6.637 ms/op
                 existUser·p1.00:   6.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15484
  mean =      2.065 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 20 
    [1.000, 1.500) = 891 
    [1.500, 2.000) = 6239 
    [2.000, 2.500) = 6522 
    [2.500, 3.000) = 1602 
    [3.000, 3.500) = 89 
    [3.500, 4.000) = 22 
    [4.000, 4.500) = 27 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 8 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.706 ms/op
     p(99.0000) =      3.253 ms/op
     p(99.9000) =      6.177 ms/op
     p(99.9900) =      6.637 ms/op
     p(99.9990) =      6.988 ms/op
     p(99.9999) =      6.988 ms/op
    p(100.0000) =      6.988 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.077 ms/op
Iteration   1: 2.109 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   2.087 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   3.236 ms/op
                 getUser·p0.999:  12.321 ms/op
                 getUser·p0.9999: 12.591 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15157
  mean =      2.109 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 12568 
    [ 2.500,  3.750) = 2392 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     12.591 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.216 ms/op
Iteration   1: 3.825 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.906 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.413 ms/op
                 listUser·p0.9999: 12.468 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8361
  mean =      3.825 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 206 
    [ 2.500,  3.750) = 3771 
    [ 3.750,  5.000) = 4026 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.906 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.413 ms/op
     p(99.9900) =     12.468 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.754          ops/ms
ClientSimple.existUser                       thrpt         13.451          ops/ms
ClientSimple.getUser                         thrpt         12.845          ops/ms
ClientSimple.listUser                        thrpt          8.983          ops/ms
ClientSimple.createUser                       avgt          2.038           ms/op
ClientSimple.existUser                        avgt          1.959           ms/op
ClientSimple.getUser                          avgt          1.719           ms/op
ClientSimple.listUser                         avgt          3.868           ms/op
ClientSimple.createUser                     sample  16332   1.957 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.425           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.868           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.488           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.763           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.047           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.121           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.723           ms/op
ClientSimple.existUser                      sample  15484   2.065 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.040           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.706           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.253           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.177           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.637           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.988           ms/op
ClientSimple.getUser                        sample  15157   2.109 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.542           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.087           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.236           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.321           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.591           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.599           ms/op
ClientSimple.listUser                       sample   8361   3.825 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.651           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.906           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.413           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.468           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.468           ms/op

Benchmark result is saved to 1714975961640.json
