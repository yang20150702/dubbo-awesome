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
# Warmup Iteration   1: 0.969 ops/ms
Iteration   1: 5.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.920 ops/ms


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
# Warmup Iteration   1: 5.871 ops/ms
Iteration   1: 12.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.798 ops/ms


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
# Warmup Iteration   1: 6.166 ops/ms
Iteration   1: 15.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.208 ops/ms


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
# Warmup Iteration   1: 4.585 ops/ms
Iteration   1: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.773 ops/ms


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.065 ms/op
Iteration   1: 2.221 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.062 ms/op
Iteration   1: 1.886 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.886 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.055 ms/op
Iteration   1: 2.042 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.089 ms/op
Iteration   1: 3.764 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.764 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.081 ms/op
Iteration   1: 2.251 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   13.140 ms/op
                 createUser·p0.999:  37.925 ms/op
                 createUser·p0.9999: 38.245 ms/op
                 createUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14316
  mean =      2.251 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12252 
    [ 2.500,  5.000) = 1830 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =     13.140 ms/op
     p(99.9000) =     37.925 ms/op
     p(99.9900) =     38.245 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.070 ms/op
Iteration   1: 1.870 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.291 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  11.187 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17203
  mean =      1.870 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 15919 
    [ 2.500,  3.750) = 820 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.363 ms/op
     p(99.9000) =     11.187 ms/op
     p(99.9900) =     11.469 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.091 ms/op
Iteration   1: 2.001 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   3.294 ms/op
                 getUser·p0.999:  13.337 ms/op
                 getUser·p0.9999: 13.786 ms/op
                 getUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15989
  mean =      2.001 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 514 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1788 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.294 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     13.786 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.135 ms/op
Iteration   1: 3.366 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.161 ms/op
                 listUser·p0.999:  28.902 ms/op
                 listUser·p0.9999: 29.655 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9496
  mean =      3.366 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1362 
    [ 2.500,  5.000) = 7893 
    [ 5.000,  7.500) = 175 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.161 ms/op
     p(99.9000) =     28.902 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.920          ops/ms
ClientSimple.existUser                       thrpt         12.798          ops/ms
ClientSimple.getUser                         thrpt         15.208          ops/ms
ClientSimple.listUser                        thrpt          8.773          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.886           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.764           ms/op
ClientSimple.createUser                     sample  14316   2.251 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.613           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.140           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.925           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.245           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.273           ms/op
ClientSimple.existUser                      sample  17203   1.870 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.291           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.363           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.187           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.469           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.469           ms/op
ClientSimple.getUser                        sample  15989   2.001 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.614           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.294           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.337           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.786           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.844           ms/op
ClientSimple.listUser                       sample   9496   3.366 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.090           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.161           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.902           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.655           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.655           ms/op

Benchmark result is saved to 1721564179598.json
