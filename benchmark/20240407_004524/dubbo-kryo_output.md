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
# Warmup Iteration   1: 1.990 ops/ms
Iteration   1: 7.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.189 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.316 ops/ms
Iteration   1: 12.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.298 ops/ms


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
# Warmup Iteration   1: 5.085 ops/ms
Iteration   1: 12.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.340 ops/ms


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
# Warmup Iteration   1: 5.238 ops/ms
Iteration   1: 8.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.426 ops/ms


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.071 ms/op
Iteration   1: 2.112 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.112 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.068 ms/op
Iteration   1: 1.836 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.836 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.068 ms/op
Iteration   1: 2.130 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.130 ms/op


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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.097 ms/op
Iteration   1: 3.799 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.799 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.077 ms/op
Iteration   1: 2.478 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   2.318 ms/op
                 createUser·p0.90:   2.859 ms/op
                 createUser·p0.95:   3.185 ms/op
                 createUser·p0.99:   12.915 ms/op
                 createUser·p0.999:  30.088 ms/op
                 createUser·p0.9999: 30.600 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12886
  mean =      2.478 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9096 
    [ 2.500,  5.000) = 3537 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.318 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.185 ms/op
     p(99.0000) =     12.915 ms/op
     p(99.9000) =     30.088 ms/op
     p(99.9900) =     30.600 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 2.772 ±(99.9%) 0.067 ms/op
Iteration   1: 1.911 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.382 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.032 ms/op
                 existUser·p0.9999: 8.048 ms/op
                 existUser·p1.00:   10.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16723
  mean =      1.911 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 52 
    [ 1.000,  2.000) = 11513 
    [ 2.000,  3.000) = 4866 
    [ 3.000,  4.000) = 168 
    [ 4.000,  5.000) = 52 
    [ 5.000,  6.000) = 41 
    [ 6.000,  7.000) = 30 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.382 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.032 ms/op
     p(99.9900) =      8.048 ms/op
     p(99.9990) =     10.224 ms/op
     p(99.9999) =     10.224 ms/op
    p(100.0000) =     10.224 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.070 ms/op
Iteration   1: 2.131 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.916 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  16.974 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15005
  mean =      2.131 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 12391 
    [ 2.500,  3.750) = 2142 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.115 ms/op
Iteration   1: 3.666 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   5.887 ms/op
                 listUser·p0.999:  7.011 ms/op
                 listUser·p0.9999: 7.692 ms/op
                 listUser·p1.00:   7.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8733
  mean =      3.666 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 32 
    [2.000, 2.500) = 342 
    [2.500, 3.000) = 1745 
    [3.000, 3.500) = 1837 
    [3.500, 4.000) = 1940 
    [4.000, 4.500) = 1464 
    [4.500, 5.000) = 920 
    [5.000, 5.500) = 290 
    [5.500, 6.000) = 84 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 32 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      5.887 ms/op
     p(99.9000) =      7.011 ms/op
     p(99.9900) =      7.692 ms/op
     p(99.9990) =      7.692 ms/op
     p(99.9999) =      7.692 ms/op
    p(100.0000) =      7.692 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.189          ops/ms
ClientSimple.existUser                       thrpt         12.298          ops/ms
ClientSimple.getUser                         thrpt         12.340          ops/ms
ClientSimple.listUser                        thrpt          8.426          ops/ms
ClientSimple.createUser                       avgt          2.112           ms/op
ClientSimple.existUser                        avgt          1.836           ms/op
ClientSimple.getUser                          avgt          2.130           ms/op
ClientSimple.listUser                         avgt          3.799           ms/op
ClientSimple.createUser                     sample  12886   2.478 ± 0.058   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.496           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.318           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.185           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.915           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.088           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.600           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.638           ms/op
ClientSimple.existUser                      sample  16723   1.911 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.584           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.382           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.465           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.032           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          8.048           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.224           ms/op
ClientSimple.getUser                        sample  15005   2.131 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.605           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.145           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.974           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.695           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.727           ms/op
ClientSimple.listUser                       sample   8733   3.666 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.317           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.022           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.887           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.011           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.692           ms/op

Benchmark result is saved to 1712450483725.json
