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
# Warmup Iteration   1: 0.628 ops/ms
Iteration   1: 6.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.601 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.755 ops/ms
Iteration   1: 13.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.402 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.969 ops/ms
Iteration   1: 11.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.039 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ops/ms
Iteration   1: 9.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.418 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ±(99.9%) 0.087 ms/op
Iteration   1: 2.272 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.272 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.174 ±(99.9%) 0.040 ms/op
Iteration   1: 1.723 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ±(99.9%) 0.053 ms/op
Iteration   1: 1.751 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.751 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.086 ms/op
Iteration   1: 3.227 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.227 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.311 ±(99.9%) 0.076 ms/op
Iteration   1: 2.046 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.271 ms/op
                 createUser·p0.50:   1.774 ms/op
                 createUser·p0.90:   2.525 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 22.145 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15624
  mean =      2.046 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13987 
    [ 2.500,  5.000) = 1353 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.525 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     22.145 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ±(99.9%) 0.063 ms/op
Iteration   1: 2.076 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.007 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  23.888 ms/op
                 existUser·p0.9999: 24.366 ms/op
                 existUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15405
  mean =      2.076 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14519 
    [ 2.500,  5.000) = 788 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     24.366 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ±(99.9%) 0.077 ms/op
Iteration   1: 2.179 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.988 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  12.676 ms/op
                 getUser·p0.9999: 12.976 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14669
  mean =      2.179 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 12422 
    [ 2.500,  3.750) = 2000 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.988 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     12.676 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.136 ms/op
Iteration   1: 3.277 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.103 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  33.136 ms/op
                 listUser·p0.9999: 33.882 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9765
  mean =      3.277 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 887 
    [ 2.500,  5.000) = 8729 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.103 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     33.136 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.601          ops/ms
ClientSimple.existUser                       thrpt         13.402          ops/ms
ClientSimple.getUser                         thrpt         11.039          ops/ms
ClientSimple.listUser                        thrpt          9.418          ops/ms
ClientSimple.createUser                       avgt          2.272           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          1.751           ms/op
ClientSimple.listUser                         avgt          3.227           ms/op
ClientSimple.createUser                     sample  15624   2.046 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.271           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.774           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.525           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.765           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.906           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.145           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.348           ms/op
ClientSimple.existUser                      sample  15405   2.076 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.702           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.342           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.888           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.366           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.543           ms/op
ClientSimple.getUser                        sample  14669   2.179 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.839           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.988           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.760           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.676           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.976           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.976           ms/op
ClientSimple.listUser                       sample   9765   3.277 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.668           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.088           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.895           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.103           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.636           ms/op
ClientSimple.listUser:listUser·p0.999       sample         33.136           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.882           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.882           ms/op

Benchmark result is saved to 1716424748763.json
