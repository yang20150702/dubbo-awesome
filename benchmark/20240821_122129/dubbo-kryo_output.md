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
# Warmup Iteration   1: 1.005 ops/ms
Iteration   1: 5.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.452 ops/ms


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
# Warmup Iteration   1: 6.578 ops/ms
Iteration   1: 13.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.673 ops/ms


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
# Warmup Iteration   1: 5.158 ops/ms
Iteration   1: 11.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.526 ops/ms


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
# Warmup Iteration   1: 5.221 ops/ms
Iteration   1: 8.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.826 ops/ms


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.069 ms/op
Iteration   1: 2.089 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.046 ms/op
Iteration   1: 2.093 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.093 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.096 ms/op
Iteration   1: 2.274 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.274 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.089 ms/op
Iteration   1: 3.320 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.320 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.102 ms/op
Iteration   1: 2.143 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   2.998 ms/op
                 createUser·p0.99:   3.657 ms/op
                 createUser·p0.999:  15.137 ms/op
                 createUser·p0.9999: 16.648 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14911
  mean =      2.143 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 11928 
    [ 2.500,  3.750) = 2791 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      3.657 ms/op
     p(99.9000) =     15.137 ms/op
     p(99.9900) =     16.648 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 2.967 ±(99.9%) 0.073 ms/op
Iteration   1: 1.777 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.602 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.281 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 13.940 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17990
  mean =      1.777 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 557 
    [ 1.250,  2.500) = 16004 
    [ 2.500,  3.750) = 1300 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.602 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     13.940 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.089 ms/op
Iteration   1: 2.094 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   2.900 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 20.233 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15261
  mean =      2.094 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13598 
    [ 2.500,  5.000) = 1630 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      2.900 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     20.233 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.120 ms/op
Iteration   1: 3.391 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.359 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  21.939 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9473
  mean =      3.391 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1084 
    [ 2.500,  5.000) = 8138 
    [ 5.000,  7.500) = 219 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     21.939 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.452          ops/ms
ClientSimple.existUser                       thrpt         13.673          ops/ms
ClientSimple.getUser                         thrpt         11.526          ops/ms
ClientSimple.listUser                        thrpt          8.826          ops/ms
ClientSimple.createUser                       avgt          2.089           ms/op
ClientSimple.existUser                        avgt          2.093           ms/op
ClientSimple.getUser                          avgt          2.274           ms/op
ClientSimple.listUser                         avgt          3.320           ms/op
ClientSimple.createUser                     sample  14911   2.143 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.624           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.657           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.648           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.203           ms/op
ClientSimple.existUser                      sample  17990   1.777 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.547           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.602           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.281           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.271           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.940           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.057           ms/op
ClientSimple.getUser                        sample  15261   2.094 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.399           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.923           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.233           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.251           ms/op
ClientSimple.listUser                       sample   9473   3.391 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.359           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.145           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.792           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.939           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.413           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.413           ms/op

Benchmark result is saved to 1724242632462.json
