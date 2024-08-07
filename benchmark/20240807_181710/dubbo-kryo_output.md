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
# Warmup Iteration   1: 1.634 ops/ms
Iteration   1: 6.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.956 ops/ms


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
# Warmup Iteration   1: 6.027 ops/ms
Iteration   1: 12.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.954 ops/ms


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
# Warmup Iteration   1: 5.983 ops/ms
Iteration   1: 15.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.450 ops/ms


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
# Warmup Iteration   1: 5.097 ops/ms
Iteration   1: 8.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.709 ops/ms


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.061 ms/op
Iteration   1: 1.948 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.948 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.046 ms/op
Iteration   1: 1.907 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.071 ms/op
Iteration   1: 2.285 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.285 ms/op


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.110 ms/op
Iteration   1: 3.655 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.655 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.088 ms/op
Iteration   1: 2.361 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   3.141 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  16.743 ms/op
                 createUser·p0.9999: 17.705 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13540
  mean =      2.361 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 10064 
    [ 2.500,  3.750) = 3115 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.141 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     16.743 ms/op
     p(99.9900) =     17.705 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.086 ms/op
Iteration   1: 2.105 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.200 ms/op
                 existUser·p0.50:   2.032 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.785 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  15.335 ms/op
                 existUser·p0.9999: 15.791 ms/op
                 existUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15180
  mean =      2.105 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 431 
    [ 1.250,  2.500) = 12445 
    [ 2.500,  3.750) = 2132 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.200 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     15.791 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.082 ms/op
Iteration   1: 2.212 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   2.083 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   4.165 ms/op
                 getUser·p0.999:  49.997 ms/op
                 getUser·p0.9999: 53.298 ms/op
                 getUser·p1.00:   53.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14552
  mean =      2.212 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14474 
    [ 5.000, 10.000) = 39 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 8 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.165 ms/op
     p(99.9000) =     49.997 ms/op
     p(99.9900) =     53.298 ms/op
     p(99.9990) =     53.805 ms/op
     p(99.9999) =     53.805 ms/op
    p(100.0000) =     53.805 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.146 ms/op
Iteration   1: 3.565 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.818 ms/op
                 listUser·p0.999:  6.399 ms/op
                 listUser·p0.9999: 7.283 ms/op
                 listUser·p1.00:   7.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8977
  mean =      3.565 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 97 
    [2.000, 2.500) = 885 
    [2.500, 3.000) = 1248 
    [3.000, 3.500) = 1619 
    [3.500, 4.000) = 2698 
    [4.000, 4.500) = 1565 
    [4.500, 5.000) = 562 
    [5.000, 5.500) = 133 
    [5.500, 6.000) = 104 
    [6.000, 6.500) = 53 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.818 ms/op
     p(99.9000) =      6.399 ms/op
     p(99.9900) =      7.283 ms/op
     p(99.9990) =      7.283 ms/op
     p(99.9999) =      7.283 ms/op
    p(100.0000) =      7.283 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.956          ops/ms
ClientSimple.existUser                       thrpt         12.954          ops/ms
ClientSimple.getUser                         thrpt         15.450          ops/ms
ClientSimple.listUser                        thrpt          8.709          ops/ms
ClientSimple.createUser                       avgt          1.948           ms/op
ClientSimple.existUser                        avgt          1.907           ms/op
ClientSimple.getUser                          avgt          2.285           ms/op
ClientSimple.listUser                         avgt          3.655           ms/op
ClientSimple.createUser                     sample  13540   2.361 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.938           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.141           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.832           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.743           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.705           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.088           ms/op
ClientSimple.existUser                      sample  15180   2.105 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.200           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.032           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.268           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.335           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.791           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.876           ms/op
ClientSimple.getUser                        sample  14552   2.212 ± 0.059   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.547           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.083           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.165           ms/op
ClientSimple.getUser:getUser·p0.999         sample         49.997           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         53.298           ms/op
ClientSimple.getUser:getUser·p1.00          sample         53.805           ms/op
ClientSimple.listUser                       sample   8977   3.565 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.818           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.399           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.283           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.283           ms/op

Benchmark result is saved to 1723054353140.json
