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
# Warmup Iteration   1: 1.648 ops/ms
Iteration   1: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.180 ops/ms


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
# Warmup Iteration   1: 5.453 ops/ms
Iteration   1: 12.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.344 ops/ms


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
# Warmup Iteration   1: 5.498 ops/ms
Iteration   1: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.787 ops/ms


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
# Warmup Iteration   1: 4.992 ops/ms
Iteration   1: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.209 ops/ms


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.069 ms/op
Iteration   1: 2.205 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.205 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.059 ms/op
Iteration   1: 2.106 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.106 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.054 ms/op
Iteration   1: 1.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.717 ms/op


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.078 ms/op
Iteration   1: 3.262 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.262 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.096 ms/op
Iteration   1: 2.235 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   1.982 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  17.869 ms/op
                 createUser·p0.9999: 18.172 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14307
  mean =      2.235 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 10770 
    [ 2.500,  3.750) = 3090 
    [ 3.750,  5.000) = 204 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     17.869 ms/op
     p(99.9900) =     18.172 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.031 ±(99.9%) 0.066 ms/op
Iteration   1: 2.122 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   2.083 ms/op
                 existUser·p0.90:   2.728 ms/op
                 existUser·p0.95:   2.937 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  15.352 ms/op
                 existUser·p0.9999: 15.811 ms/op
                 existUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15061
  mean =      2.122 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 497 
    [ 1.250,  2.500) = 11744 
    [ 2.500,  3.750) = 2753 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.359 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     15.811 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.097 ms/op
Iteration   1: 1.928 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.410 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.294 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  14.811 ms/op
                 getUser·p0.9999: 19.410 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16565
  mean =      1.928 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 219 
    [ 1.250,  2.500) = 15642 
    [ 2.500,  3.750) = 520 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     19.410 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.490 ±(99.9%) 0.135 ms/op
Iteration   1: 3.479 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.626 ms/op
                 listUser·p0.999:  21.128 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9212
  mean =      3.479 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1806 
    [ 2.500,  5.000) = 7017 
    [ 5.000,  7.500) = 290 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.626 ms/op
     p(99.9000) =     21.128 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.180          ops/ms
ClientSimple.existUser                       thrpt         12.344          ops/ms
ClientSimple.getUser                         thrpt         10.787          ops/ms
ClientSimple.listUser                        thrpt          8.209          ops/ms
ClientSimple.createUser                       avgt          2.205           ms/op
ClientSimple.existUser                        avgt          2.106           ms/op
ClientSimple.getUser                          avgt          1.717           ms/op
ClientSimple.listUser                         avgt          3.262           ms/op
ClientSimple.createUser                     sample  14307   2.235 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.783           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.982           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.330           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.850           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.869           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.172           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.186           ms/op
ClientSimple.existUser                      sample  15061   2.122 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.937           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.359           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.352           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.811           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.811           ms/op
ClientSimple.getUser                        sample  16565   1.928 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.410           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.170           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.811           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.410           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.431           ms/op
ClientSimple.listUser                       sample   9212   3.479 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.774           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.626           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.128           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.299           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.299           ms/op

Benchmark result is saved to 1718066445584.json
