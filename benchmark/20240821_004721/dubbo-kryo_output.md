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
# Warmup Iteration   1: 1.665 ops/ms
Iteration   1: 6.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.595 ops/ms


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
# Warmup Iteration   1: 6.416 ops/ms
Iteration   1: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.505 ops/ms


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
# Warmup Iteration   1: 5.588 ops/ms
Iteration   1: 14.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.047 ops/ms


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
# Warmup Iteration   1: 4.434 ops/ms
Iteration   1: 8.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.276 ops/ms


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.062 ms/op
Iteration   1: 2.143 ±(99.9%) 0.013 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.052 ms/op
Iteration   1: 1.842 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.842 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.055 ms/op
Iteration   1: 2.121 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.121 ms/op


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.098 ms/op
Iteration   1: 3.333 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.333 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.092 ms/op
Iteration   1: 2.179 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.376 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   6.544 ms/op
                 createUser·p0.999:  26.563 ms/op
                 createUser·p0.9999: 27.938 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14673
  mean =      2.179 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12704 
    [ 2.500,  5.000) = 1720 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      6.544 ms/op
     p(99.9000) =     26.563 ms/op
     p(99.9900) =     27.938 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.075 ms/op
Iteration   1: 1.627 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   1.587 ms/op
                 existUser·p0.90:   1.866 ms/op
                 existUser·p0.95:   1.970 ms/op
                 existUser·p0.99:   2.650 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 13.190 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19637
  mean =      1.627 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 458 
    [ 1.250,  2.500) = 18936 
    [ 2.500,  3.750) = 141 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.587 ms/op
     p(90.0000) =      1.866 ms/op
     p(95.0000) =      1.970 ms/op
     p(99.0000) =      2.650 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     13.190 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.034 ±(99.9%) 0.076 ms/op
Iteration   1: 2.011 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.523 ms/op
                 getUser·p0.99:   4.501 ms/op
                 getUser·p0.999:  19.440 ms/op
                 getUser·p0.9999: 20.487 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15912
  mean =      2.011 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14984 
    [ 2.500,  5.000) = 814 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      4.501 ms/op
     p(99.9000) =     19.440 ms/op
     p(99.9900) =     20.487 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.139 ms/op
Iteration   1: 3.147 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.262 ms/op
                 listUser·p0.999:  14.842 ms/op
                 listUser·p0.9999: 16.136 ms/op
                 listUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10144
  mean =      3.147 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 829 
    [ 2.500,  3.750) = 7462 
    [ 3.750,  5.000) = 1666 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.262 ms/op
     p(99.9000) =     14.842 ms/op
     p(99.9900) =     16.136 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.595          ops/ms
ClientSimple.existUser                       thrpt         12.505          ops/ms
ClientSimple.getUser                         thrpt         14.047          ops/ms
ClientSimple.listUser                        thrpt          8.276          ops/ms
ClientSimple.createUser                       avgt          2.143           ms/op
ClientSimple.existUser                        avgt          1.842           ms/op
ClientSimple.getUser                          avgt          2.121           ms/op
ClientSimple.listUser                         avgt          3.333           ms/op
ClientSimple.createUser                     sample  14673   2.179 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.376           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.544           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.563           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.938           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.213           ms/op
ClientSimple.existUser                      sample  19637   1.627 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.513           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.587           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.866           ms/op
ClientSimple.existUser:existUser·p0.95      sample          1.970           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.960           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.190           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.222           ms/op
ClientSimple.getUser                        sample  15912   2.011 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.523           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.501           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.440           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.487           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.546           ms/op
ClientSimple.listUser                       sample  10144   3.147 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.793           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.863           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.262           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.842           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.136           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.138           ms/op

Benchmark result is saved to 1724200993815.json
