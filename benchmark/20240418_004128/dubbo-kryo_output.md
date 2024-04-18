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
# Warmup Iteration   1: 2.192 ops/ms
Iteration   1: 6.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.904 ops/ms


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
# Warmup Iteration   1: 5.381 ops/ms
Iteration   1: 11.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.838 ops/ms


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
# Warmup Iteration   1: 5.827 ops/ms
Iteration   1: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.877 ops/ms


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
# Warmup Iteration   1: 5.608 ops/ms
Iteration   1: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.602 ops/ms


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.067 ms/op
Iteration   1: 2.113 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.113 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.059 ms/op
Iteration   1: 1.627 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.627 ms/op


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
# Warmup Iteration   1: 3.237 ±(99.9%) 0.077 ms/op
Iteration   1: 2.029 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.029 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.068 ms/op
Iteration   1: 3.877 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.877 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.092 ms/op
Iteration   1: 2.312 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.802 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  36.045 ms/op
                 createUser·p0.9999: 41.242 ms/op
                 createUser·p1.00:   41.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13917
  mean =      2.312 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13657 
    [ 5.000, 10.000) = 164 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     36.045 ms/op
     p(99.9900) =     41.242 ms/op
     p(99.9990) =     41.550 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


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
# Warmup Iteration   1: 2.911 ±(99.9%) 0.063 ms/op
Iteration   1: 1.850 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.374 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.118 ms/op
                 existUser·p0.999:  22.073 ms/op
                 existUser·p0.9999: 22.291 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17393
  mean =      1.850 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16485 
    [ 2.500,  5.000) = 812 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.118 ms/op
     p(99.9000) =     22.073 ms/op
     p(99.9900) =     22.291 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.104 ms/op
Iteration   1: 2.081 ±(99.9%) 0.077 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.503 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  47.553 ms/op
                 getUser·p0.9999: 47.932 ms/op
                 getUser·p1.00:   48.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15403
  mean =      2.081 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15218 
    [ 5.000, 10.000) = 80 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 36 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     47.553 ms/op
     p(99.9900) =     47.932 ms/op
     p(99.9990) =     48.038 ms/op
     p(99.9999) =     48.038 ms/op
    p(100.0000) =     48.038 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.130 ms/op
Iteration   1: 3.521 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.469 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  21.652 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9080
  mean =      3.521 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 798 
    [ 2.500,  5.000) = 8085 
    [ 5.000,  7.500) = 132 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     21.652 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.904          ops/ms
ClientSimple.existUser                       thrpt         11.838          ops/ms
ClientSimple.getUser                         thrpt         12.877          ops/ms
ClientSimple.listUser                        thrpt          8.602          ops/ms
ClientSimple.createUser                       avgt          2.113           ms/op
ClientSimple.existUser                        avgt          1.627           ms/op
ClientSimple.getUser                          avgt          2.029           ms/op
ClientSimple.listUser                         avgt          3.877           ms/op
ClientSimple.createUser                     sample  13917   2.312 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.415           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.146           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.258           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.045           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.242           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.550           ms/op
ClientSimple.existUser                      sample  17393   1.850 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.374           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.118           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.073           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.291           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.315           ms/op
ClientSimple.getUser                        sample  15403   2.081 ± 0.077   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.586           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.366           ms/op
ClientSimple.getUser:getUser·p0.999         sample         47.553           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         47.932           ms/op
ClientSimple.getUser:getUser·p1.00          sample         48.038           ms/op
ClientSimple.listUser                       sample   9080   3.521 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.794           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.469           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.652           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.479           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.479           ms/op

Benchmark result is saved to 1713400635180.json
