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
# Warmup Iteration   1: 1.699 ops/ms
Iteration   1: 6.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.879 ops/ms


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
# Warmup Iteration   1: 5.579 ops/ms
Iteration   1: 11.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.812 ops/ms


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
# Warmup Iteration   1: 5.664 ops/ms
Iteration   1: 13.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.589 ops/ms


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
# Warmup Iteration   1: 5.776 ops/ms
Iteration   1: 10.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.233 ops/ms


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.061 ms/op
Iteration   1: 2.122 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.122 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ±(99.9%) 0.039 ms/op
Iteration   1: 1.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.063 ms/op
Iteration   1: 1.975 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.975 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ±(99.9%) 0.082 ms/op
Iteration   1: 3.178 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.178 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.648 ±(99.9%) 0.094 ms/op
Iteration   1: 2.083 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   1.931 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.658 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 19.210 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15376
  mean =      2.083 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 13941 
    [ 2.500,  3.750) = 1043 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     19.210 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.844 ±(99.9%) 0.060 ms/op
Iteration   1: 1.726 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   1.612 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   3.165 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18524
  mean =      1.726 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17920 
    [ 2.500,  5.000) = 540 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.612 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.165 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.084 ms/op
Iteration   1: 1.989 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   3.829 ms/op
                 getUser·p0.999:  10.797 ms/op
                 getUser·p0.9999: 11.624 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16171
  mean =      1.989 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 14430 
    [ 2.500,  3.750) = 1289 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.829 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     11.624 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.111 ms/op
Iteration   1: 3.368 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.908 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9487
  mean =      3.368 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 574 
    [ 2.500,  3.750) = 6585 
    [ 3.750,  5.000) = 2125 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.908 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.879          ops/ms
ClientSimple.existUser                       thrpt         11.812          ops/ms
ClientSimple.getUser                         thrpt         13.589          ops/ms
ClientSimple.listUser                        thrpt         10.233          ops/ms
ClientSimple.createUser                       avgt          2.122           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          1.975           ms/op
ClientSimple.listUser                         avgt          3.178           ms/op
ClientSimple.createUser                     sample  15376   2.083 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.931           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.241           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.645           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.210           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  18524   1.726 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.699           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.612           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.175           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.165           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.578           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.840           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.840           ms/op
ClientSimple.getUser                        sample  16171   1.989 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.513           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.829           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.797           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.624           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.715           ms/op
ClientSimple.listUser                       sample   9487   3.368 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.908           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.107           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.597           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.597           ms/op

Benchmark result is saved to 1723551490965.json
