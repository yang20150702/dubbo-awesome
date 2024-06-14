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
# Warmup Iteration   1: 1.626 ops/ms
Iteration   1: 7.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.529 ops/ms


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
# Warmup Iteration   1: 6.677 ops/ms
Iteration   1: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.064 ops/ms


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
# Warmup Iteration   1: 4.593 ops/ms
Iteration   1: 12.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.467 ops/ms


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
# Warmup Iteration   1: 4.923 ops/ms
Iteration   1: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.015 ops/ms


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.076 ms/op
Iteration   1: 2.220 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.220 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.063 ms/op
Iteration   1: 2.081 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.081 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.061 ms/op
Iteration   1: 2.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.065 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.107 ms/op
Iteration   1: 3.293 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.293 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.093 ms/op
Iteration   1: 2.011 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.241 ms/op
                 createUser·p0.95:   2.470 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15888
  mean =      2.011 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15160 
    [ 2.500,  5.000) = 562 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.079 ms/op
Iteration   1: 1.907 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.155 ms/op
                 existUser·p0.999:  26.025 ms/op
                 existUser·p0.9999: 26.334 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16769
  mean =      1.907 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15724 
    [ 2.500,  5.000) = 981 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.155 ms/op
     p(99.9000) =     26.025 ms/op
     p(99.9900) =     26.334 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.079 ms/op
Iteration   1: 2.126 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.390 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.802 ms/op
                 getUser·p0.95:   3.007 ms/op
                 getUser·p0.99:   4.347 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 13.908 ms/op
                 getUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15036
  mean =      2.126 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 680 
    [ 1.250,  2.500) = 10895 
    [ 2.500,  3.750) = 3226 
    [ 3.750,  5.000) = 128 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.802 ms/op
     p(95.0000) =      3.007 ms/op
     p(99.0000) =      4.347 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     13.908 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.126 ms/op
Iteration   1: 3.230 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 15.548 ms/op
                 listUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9894
  mean =      3.230 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1028 
    [ 2.500,  3.750) = 6361 
    [ 3.750,  5.000) = 2294 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     15.548 ms/op
     p(99.9990) =     15.548 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.529          ops/ms
ClientSimple.existUser                       thrpt         13.064          ops/ms
ClientSimple.getUser                         thrpt         12.467          ops/ms
ClientSimple.listUser                        thrpt          9.015          ops/ms
ClientSimple.createUser                       avgt          2.220           ms/op
ClientSimple.existUser                        avgt          2.081           ms/op
ClientSimple.getUser                          avgt          2.065           ms/op
ClientSimple.listUser                         avgt          3.293           ms/op
ClientSimple.createUser                     sample  15888   2.011 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.906           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.241           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.464           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.743           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.480           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  16769   1.907 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.413           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.155           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.025           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.334           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.378           ms/op
ClientSimple.getUser                        sample  15036   2.126 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.390           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.007           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.347           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.908           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.237           ms/op
ClientSimple.listUser                       sample   9894   3.230 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.857           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.867           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.496           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.122           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.548           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.548           ms/op

Benchmark result is saved to 1718345618246.json
