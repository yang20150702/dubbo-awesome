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
# Warmup Iteration   1: 1.353 ops/ms
Iteration   1: 5.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.991 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ops/ms
Iteration   1: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.029 ops/ms


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
# Warmup Iteration   1: 6.543 ops/ms
Iteration   1: 12.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.194 ops/ms


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
# Warmup Iteration   1: 4.870 ops/ms
Iteration   1: 9.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.156 ops/ms


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.057 ms/op
Iteration   1: 2.143 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.143 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.053 ms/op
Iteration   1: 1.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.993 ms/op


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
# Warmup Iteration   1: 2.801 ±(99.9%) 0.050 ms/op
Iteration   1: 2.375 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.375 ms/op


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
# Warmup Iteration   1: 5.105 ±(99.9%) 0.107 ms/op
Iteration   1: 3.622 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.622 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.082 ms/op
Iteration   1: 2.204 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  22.331 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14498
  mean =      2.204 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11321 
    [ 2.500,  5.000) = 3030 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     22.331 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 2.859 ±(99.9%) 0.059 ms/op
Iteration   1: 1.838 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.372 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   4.093 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 11.200 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17475
  mean =      1.838 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 374 
    [ 1.250,  2.500) = 16291 
    [ 2.500,  3.750) = 626 
    [ 3.750,  5.000) = 123 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.093 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     11.200 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.095 ms/op
Iteration   1: 1.927 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.319 ms/op
                 getUser·p0.95:   2.521 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  11.539 ms/op
                 getUser·p0.9999: 12.746 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16747
  mean =      1.927 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 15796 
    [ 2.500,  3.750) = 715 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.319 ms/op
     p(95.0000) =      2.521 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =     11.539 ms/op
     p(99.9900) =     12.746 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.974 ±(99.9%) 0.122 ms/op
Iteration   1: 3.535 ±(99.9%) 0.069 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.322 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   13.366 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 36.307 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9119
  mean =      3.535 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1263 
    [ 2.500,  5.000) = 7427 
    [ 5.000,  7.500) = 326 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =     13.366 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.991          ops/ms
ClientSimple.existUser                       thrpt         13.029          ops/ms
ClientSimple.getUser                         thrpt         12.194          ops/ms
ClientSimple.listUser                        thrpt          9.156          ops/ms
ClientSimple.createUser                       avgt          2.143           ms/op
ClientSimple.existUser                        avgt          1.993           ms/op
ClientSimple.getUser                          avgt          2.375           ms/op
ClientSimple.listUser                         avgt          3.622           ms/op
ClientSimple.createUser                     sample  14498   2.204 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.761           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.317           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.331           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.479           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.479           ms/op
ClientSimple.existUser                      sample  17475   1.838 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.372           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.093           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.633           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.200           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.813           ms/op
ClientSimple.getUser                        sample  16747   1.927 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.774           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.319           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.521           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.887           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.539           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.746           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   9119   3.535 ± 0.069   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.715           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.322           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.366           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.560           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.307           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.307           ms/op

Benchmark result is saved to 1722168939973.json
