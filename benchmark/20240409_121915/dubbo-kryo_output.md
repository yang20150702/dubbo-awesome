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
# Warmup Iteration   1: 1.927 ops/ms
Iteration   1: 5.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.756 ops/ms


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
# Warmup Iteration   1: 5.070 ops/ms
Iteration   1: 11.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.030 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ops/ms
Iteration   1: 11.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.109 ops/ms


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
# Warmup Iteration   1: 4.834 ops/ms
Iteration   1: 8.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.766 ops/ms


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.092 ms/op
Iteration   1: 1.928 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.928 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.066 ms/op
Iteration   1: 1.913 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.063 ms/op
Iteration   1: 2.225 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.225 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.083 ms/op
Iteration   1: 3.338 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.338 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.075 ms/op
Iteration   1: 2.149 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   3.018 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  29.131 ms/op
                 createUser·p0.9999: 31.293 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14865
  mean =      2.149 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13112 
    [ 2.500,  5.000) = 1576 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      3.018 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 3.235 ±(99.9%) 0.091 ms/op
Iteration   1: 1.982 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  11.842 ms/op
                 existUser·p0.9999: 12.638 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16194
  mean =      1.982 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 821 
    [ 1.250,  2.500) = 14111 
    [ 2.500,  3.750) = 1173 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =     11.842 ms/op
     p(99.9900) =     12.638 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.084 ms/op
Iteration   1: 1.802 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   1.739 ms/op
                 getUser·p0.90:   2.204 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   3.367 ms/op
                 getUser·p0.999:  11.457 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17741
  mean =      1.802 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 716 
    [ 1.250,  2.500) = 16390 
    [ 2.500,  3.750) = 516 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     11.457 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.157 ms/op
Iteration   1: 3.544 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.447 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  27.032 ms/op
                 listUser·p0.9999: 36.766 ms/op
                 listUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9023
  mean =      3.544 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 667 
    [ 2.500,  5.000) = 8111 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.447 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     27.032 ms/op
     p(99.9900) =     36.766 ms/op
     p(99.9990) =     36.766 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.756          ops/ms
ClientSimple.existUser                       thrpt         11.030          ops/ms
ClientSimple.getUser                         thrpt         11.109          ops/ms
ClientSimple.listUser                        thrpt          8.766          ops/ms
ClientSimple.createUser                       avgt          1.928           ms/op
ClientSimple.existUser                        avgt          1.913           ms/op
ClientSimple.getUser                          avgt          2.225           ms/op
ClientSimple.listUser                         avgt          3.338           ms/op
ClientSimple.createUser                     sample  14865   2.149 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.568           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.018           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.808           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.131           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.293           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.293           ms/op
ClientSimple.existUser                      sample  16194   1.982 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.602           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.396           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.842           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.638           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.500           ms/op
ClientSimple.getUser                        sample  17741   1.802 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.669           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.739           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.367           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.457           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.682           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.682           ms/op
ClientSimple.listUser                       sample   9023   3.544 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.957           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.447           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.881           ms/op
ClientSimple.listUser:listUser·p0.999       sample         27.032           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.766           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.766           ms/op

Benchmark result is saved to 1712664907870.json
