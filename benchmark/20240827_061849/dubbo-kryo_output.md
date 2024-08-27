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
# Warmup Iteration   1: 1.268 ops/ms
Iteration   1: 5.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.777 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ops/ms
Iteration   1: 12.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.181 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.542 ops/ms
Iteration   1: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.731 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ops/ms
Iteration   1: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.365 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ±(99.9%) 0.083 ms/op
Iteration   1: 2.397 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.397 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ±(99.9%) 0.065 ms/op
Iteration   1: 1.945 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.945 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.055 ms/op
Iteration   1: 1.985 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.095 ms/op
Iteration   1: 3.357 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.357 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.102 ms/op
Iteration   1: 2.215 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   6.143 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 19.650 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14433
  mean =      2.215 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 11896 
    [ 2.500,  3.750) = 2129 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      6.143 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.650 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.075 ms/op
Iteration   1: 2.093 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.740 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   5.574 ms/op
                 existUser·p0.999:  16.530 ms/op
                 existUser·p0.9999: 17.312 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15361
  mean =      2.093 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 265 
    [ 1.250,  2.500) = 12575 
    [ 2.500,  3.750) = 2216 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     16.530 ms/op
     p(99.9900) =     17.312 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.091 ms/op
Iteration   1: 2.136 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.912 ms/op
                 getUser·p0.95:   3.333 ms/op
                 getUser·p0.99:   5.598 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 12.001 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14983
  mean =      2.136 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 462 
    [ 1.250,  2.500) = 11562 
    [ 2.500,  3.750) = 2503 
    [ 3.750,  5.000) = 229 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.333 ms/op
     p(99.0000) =      5.598 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     12.001 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.119 ms/op
Iteration   1: 3.248 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.650 ms/op
                 listUser·p0.9999: 15.319 ms/op
                 listUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9847
  mean =      3.248 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1432 
    [ 2.500,  3.750) = 6378 
    [ 3.750,  5.000) = 1730 
    [ 5.000,  6.250) = 174 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     14.650 ms/op
     p(99.9900) =     15.319 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.777          ops/ms
ClientSimple.existUser                       thrpt         12.181          ops/ms
ClientSimple.getUser                         thrpt         12.731          ops/ms
ClientSimple.listUser                        thrpt          8.365          ops/ms
ClientSimple.createUser                       avgt          2.397           ms/op
ClientSimple.existUser                        avgt          1.945           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.357           ms/op
ClientSimple.createUser                     sample  14433   2.215 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.650           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.143           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.650           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.694           ms/op
ClientSimple.existUser                      sample  15361   2.093 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.986           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.574           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.530           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.312           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.400           ms/op
ClientSimple.getUser                        sample  14983   2.136 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.872           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.333           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.598           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.928           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.001           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample   9847   3.248 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.340           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.650           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.319           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.319           ms/op

Benchmark result is saved to 1724739258830.json
