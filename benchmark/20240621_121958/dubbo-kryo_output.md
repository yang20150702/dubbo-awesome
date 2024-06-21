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
# Warmup Iteration   1: 1.778 ops/ms
Iteration   1: 7.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.156 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ops/ms
Iteration   1: 12.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.240 ops/ms


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
# Warmup Iteration   1: 6.399 ops/ms
Iteration   1: 15.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.515 ops/ms


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
# Warmup Iteration   1: 5.162 ops/ms
Iteration   1: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.103 ops/ms


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.079 ms/op
Iteration   1: 2.294 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.294 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.064 ms/op
Iteration   1: 1.978 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.065 ms/op
Iteration   1: 2.074 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.074 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.074 ms/op
Iteration   1: 3.382 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.382 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.129 ms/op
Iteration   1: 2.359 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 22.191 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13621
  mean =      2.359 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10444 
    [ 2.500,  5.000) = 2843 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     22.191 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 2.773 ±(99.9%) 0.066 ms/op
Iteration   1: 2.084 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.605 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  21.714 ms/op
                 existUser·p0.9999: 22.769 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15328
  mean =      2.084 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13479 
    [ 2.500,  5.000) = 1630 
    [ 5.000,  7.500) = 112 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     21.714 ms/op
     p(99.9900) =     22.769 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.103 ms/op
Iteration   1: 2.033 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.722 ms/op
                 getUser·p0.999:  14.945 ms/op
                 getUser·p0.9999: 15.342 ms/op
                 getUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15838
  mean =      2.033 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 14615 
    [ 2.500,  3.750) = 929 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.722 ms/op
     p(99.9000) =     14.945 ms/op
     p(99.9900) =     15.342 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 6.421 ±(99.9%) 0.210 ms/op
Iteration   1: 3.902 ±(99.9%) 0.105 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   8.009 ms/op
                 listUser·p0.999:  49.465 ms/op
                 listUser·p0.9999: 53.019 ms/op
                 listUser·p1.00:   53.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8218
  mean =      3.902 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7729 
    [ 5.000, 10.000) = 421 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 17 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      8.009 ms/op
     p(99.9000) =     49.465 ms/op
     p(99.9900) =     53.019 ms/op
     p(99.9990) =     53.019 ms/op
     p(99.9999) =     53.019 ms/op
    p(100.0000) =     53.019 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.156          ops/ms
ClientSimple.existUser                       thrpt         12.240          ops/ms
ClientSimple.getUser                         thrpt         15.515          ops/ms
ClientSimple.listUser                        thrpt          9.103          ops/ms
ClientSimple.createUser                       avgt          2.294           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          2.074           ms/op
ClientSimple.listUser                         avgt          3.382           ms/op
ClientSimple.createUser                     sample  13621   2.359 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.428           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.011           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.398           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.191           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.381           ms/op
ClientSimple.existUser                      sample  15328   2.084 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.690           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.882           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.974           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.480           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.714           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.769           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.839           ms/op
ClientSimple.getUser                        sample  15838   2.033 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.535           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.722           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.342           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.352           ms/op
ClientSimple.listUser                       sample   8218   3.902 ± 0.105   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.887           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.715           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.009           ms/op
ClientSimple.listUser:listUser·p0.999       sample         49.465           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         53.019           ms/op
ClientSimple.listUser:listUser·p1.00        sample         53.019           ms/op

Benchmark result is saved to 1718972160763.json
