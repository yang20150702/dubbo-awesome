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
# Warmup Iteration   1: 1.690 ops/ms
Iteration   1: 6.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.523 ops/ms


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
# Warmup Iteration   1: 5.393 ops/ms
Iteration   1: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.869 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 12.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.933 ops/ms


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
# Warmup Iteration   1: 5.918 ops/ms
Iteration   1: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.685 ops/ms


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.069 ms/op
Iteration   1: 2.394 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.394 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.058 ms/op
Iteration   1: 1.826 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.826 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.058 ms/op
Iteration   1: 2.540 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.540 ms/op


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.091 ms/op
Iteration   1: 3.250 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.250 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.108 ms/op
Iteration   1: 2.132 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   5.727 ms/op
                 createUser·p0.999:  22.447 ms/op
                 createUser·p0.9999: 22.856 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14956
  mean =      2.132 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13167 
    [ 2.500,  5.000) = 1523 
    [ 5.000,  7.500) = 202 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.727 ms/op
     p(99.9000) =     22.447 ms/op
     p(99.9900) =     22.856 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.081 ms/op
Iteration   1: 2.110 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.368 ms/op
                 existUser·p0.50:   1.993 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   7.293 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 20.471 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15154
  mean =      2.110 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13247 
    [ 2.500,  5.000) = 1694 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      7.293 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     20.471 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.092 ms/op
Iteration   1: 1.916 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   3.118 ms/op
                 getUser·p0.999:  12.814 ms/op
                 getUser·p0.9999: 13.173 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16867
  mean =      1.916 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 15468 
    [ 2.500,  3.750) = 1105 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.118 ms/op
     p(99.9000) =     12.814 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.152 ms/op
Iteration   1: 3.265 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.089 ms/op
                 listUser·p0.999:  5.744 ms/op
                 listUser·p0.9999: 8.536 ms/op
                 listUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9888
  mean =      3.265 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 23 
    [2.000, 2.500) = 190 
    [2.500, 3.000) = 4541 
    [3.000, 3.500) = 1872 
    [3.500, 4.000) = 1859 
    [4.000, 4.500) = 1027 
    [4.500, 5.000) = 250 
    [5.000, 5.500) = 71 
    [5.500, 6.000) = 37 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.089 ms/op
     p(99.9000) =      5.744 ms/op
     p(99.9900) =      8.536 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.523          ops/ms
ClientSimple.existUser                       thrpt         12.869          ops/ms
ClientSimple.getUser                         thrpt         12.933          ops/ms
ClientSimple.listUser                        thrpt          8.685          ops/ms
ClientSimple.createUser                       avgt          2.394           ms/op
ClientSimple.existUser                        avgt          1.826           ms/op
ClientSimple.getUser                          avgt          2.540           ms/op
ClientSimple.listUser                         avgt          3.250           ms/op
ClientSimple.createUser                     sample  14956   2.132 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.727           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.447           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.856           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.872           ms/op
ClientSimple.existUser                      sample  15154   2.110 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.368           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.993           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.464           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.471           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.775           ms/op
ClientSimple.getUser                        sample  16867   1.916 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.563           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.118           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.814           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.173           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9888   3.265 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.031           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.089           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.744           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.536           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.536           ms/op

Benchmark result is saved to 1721695375814.json
