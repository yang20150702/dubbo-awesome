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
# Warmup Iteration   1: 2.013 ops/ms
Iteration   1: 6.357 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.357 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.036 ops/ms
Iteration   1: 12.165 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.165 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ops/ms
Iteration   1: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.098 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.007 ops/ms
Iteration   1: 3.249 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.249 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.928 ±(99.9%) 0.084 ms/op
Iteration   1: 3.137 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.137 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.449 ±(99.9%) 0.037 ms/op
Iteration   1: 1.984 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.067 ms/op
Iteration   1: 3.192 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.192 ms/op


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
# Warmup Iteration   1: 12.727 ±(99.9%) 0.229 ms/op
Iteration   1: 8.650 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.650 ms/op


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
# Warmup Iteration   1: 5.681 ±(99.9%) 0.189 ms/op
Iteration   1: 3.412 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   8.653 ms/op
                 createUser·p0.999:  16.394 ms/op
                 createUser·p0.9999: 16.515 ms/op
                 createUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9385
  mean =      3.412 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 694 
    [ 2.500,  3.750) = 6325 
    [ 3.750,  5.000) = 1840 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.653 ms/op
     p(99.9000) =     16.394 ms/op
     p(99.9900) =     16.515 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ±(99.9%) 0.067 ms/op
Iteration   1: 1.849 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   3.142 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 6.875 ms/op
                 existUser·p1.00:   6.881 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17277
  mean =      1.849 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 95 
    [1.000, 1.500) = 2089 
    [1.500, 2.000) = 10739 
    [2.000, 2.500) = 3673 
    [2.500, 3.000) = 477 
    [3.000, 3.500) = 128 
    [3.500, 4.000) = 20 
    [4.000, 4.500) = 2 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      3.142 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =      6.875 ms/op
     p(99.9990) =      6.881 ms/op
     p(99.9999) =      6.881 ms/op
    p(100.0000) =      6.881 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ±(99.9%) 0.147 ms/op
Iteration   1: 3.393 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.507 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 9.191 ms/op
                 getUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9462
  mean =      3.393 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 31 
    [ 1.500,  2.000) = 182 
    [ 2.000,  2.500) = 865 
    [ 2.500,  3.000) = 1662 
    [ 3.000,  3.500) = 2855 
    [ 3.500,  4.000) = 2483 
    [ 4.000,  4.500) = 791 
    [ 4.500,  5.000) = 215 
    [ 5.000,  5.500) = 153 
    [ 5.500,  6.000) = 77 
    [ 6.000,  6.500) = 51 
    [ 6.500,  7.000) = 48 
    [ 7.000,  7.500) = 20 
    [ 7.500,  8.000) = 8 
    [ 8.000,  8.500) = 15 
    [ 8.500,  9.000) = 5 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.507 ms/op
     p(99.9000) =      8.237 ms/op
     p(99.9900) =      9.191 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


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
# Warmup Iteration   1: 12.426 ±(99.9%) 0.404 ms/op
Iteration   1: 8.679 ±(99.9%) 0.144 ms/op
                 listUser·p0.00:   3.191 ms/op
                 listUser·p0.50:   8.364 ms/op
                 listUser·p0.90:   10.994 ms/op
                 listUser·p0.95:   12.373 ms/op
                 listUser·p0.99:   18.711 ms/op
                 listUser·p0.999:  28.098 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3755
  mean =      8.679 ±(99.9%) 0.144 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 66 
    [ 5.000,  7.500) = 959 
    [ 7.500, 10.000) = 2084 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.191 ms/op
     p(50.0000) =      8.364 ms/op
     p(90.0000) =     10.994 ms/op
     p(95.0000) =     12.373 ms/op
     p(99.0000) =     18.711 ms/op
     p(99.9000) =     28.098 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.357          ops/ms
Client.existUser                       thrpt         12.165          ops/ms
Client.getUser                         thrpt          8.098          ops/ms
Client.listUser                        thrpt          3.249          ops/ms
Client.createUser                       avgt          3.137           ms/op
Client.existUser                        avgt          1.984           ms/op
Client.getUser                          avgt          3.192           ms/op
Client.listUser                         avgt          8.650           ms/op
Client.createUser                     sample   9385   3.412 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.257           ms/op
Client.createUser:createUser·p0.50    sample          3.056           ms/op
Client.createUser:createUser·p0.90    sample          4.358           ms/op
Client.createUser:createUser·p0.95    sample          5.267           ms/op
Client.createUser:createUser·p0.99    sample          8.653           ms/op
Client.createUser:createUser·p0.999   sample         16.394           ms/op
Client.createUser:createUser·p0.9999  sample         16.515           ms/op
Client.createUser:createUser·p1.00    sample         16.515           ms/op
Client.existUser                      sample  17277   1.849 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.600           ms/op
Client.existUser:existUser·p0.50      sample          1.800           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.425           ms/op
Client.existUser:existUser·p0.99      sample          3.142           ms/op
Client.existUser:existUser·p0.999     sample          6.685           ms/op
Client.existUser:existUser·p0.9999    sample          6.875           ms/op
Client.existUser:existUser·p1.00      sample          6.881           ms/op
Client.getUser                        sample   9462   3.393 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          1.020           ms/op
Client.getUser:getUser·p0.50          sample          3.371           ms/op
Client.getUser:getUser·p0.90          sample          4.186           ms/op
Client.getUser:getUser·p0.95          sample          4.792           ms/op
Client.getUser:getUser·p0.99          sample          6.507           ms/op
Client.getUser:getUser·p0.999         sample          8.237           ms/op
Client.getUser:getUser·p0.9999        sample          9.191           ms/op
Client.getUser:getUser·p1.00          sample          9.191           ms/op
Client.listUser                       sample   3755   8.679 ± 0.144   ms/op
Client.listUser:listUser·p0.00        sample          3.191           ms/op
Client.listUser:listUser·p0.50        sample          8.364           ms/op
Client.listUser:listUser·p0.90        sample         10.994           ms/op
Client.listUser:listUser·p0.95        sample         12.373           ms/op
Client.listUser:listUser·p0.99        sample         18.711           ms/op
Client.listUser:listUser·p0.999       sample         28.098           ms/op
Client.listUser:listUser·p0.9999      sample         34.669           ms/op
Client.listUser:listUser·p1.00        sample         34.669           ms/op
