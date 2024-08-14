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
# Warmup Iteration   1: 2.343 ops/ms
Iteration   1: 7.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.973 ops/ms


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
# Warmup Iteration   1: 6.615 ops/ms
Iteration   1: 13.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.002 ops/ms


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
# Warmup Iteration   1: 6.217 ops/ms
Iteration   1: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.083 ops/ms


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
# Warmup Iteration   1: 4.774 ops/ms
Iteration   1: 7.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.684 ops/ms


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.064 ms/op
Iteration   1: 2.252 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.252 ms/op


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
# Warmup Iteration   1: 3.089 ±(99.9%) 0.043 ms/op
Iteration   1: 1.716 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.716 ms/op


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
# Warmup Iteration   1: 3.396 ±(99.9%) 0.074 ms/op
Iteration   1: 2.150 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.150 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.097 ms/op
Iteration   1: 3.318 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.318 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.085 ms/op
Iteration   1: 2.050 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   1.866 ms/op
                 createUser·p0.90:   2.449 ms/op
                 createUser·p0.95:   2.675 ms/op
                 createUser·p0.99:   7.207 ms/op
                 createUser·p0.999:  19.510 ms/op
                 createUser·p0.9999: 27.308 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15587
  mean =      2.050 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14277 
    [ 2.500,  5.000) = 1115 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      7.207 ms/op
     p(99.9000) =     19.510 ms/op
     p(99.9900) =     27.308 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 3.010 ±(99.9%) 0.068 ms/op
Iteration   1: 1.846 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.509 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 22.234 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17310
  mean =      1.846 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16430 
    [ 2.500,  5.000) = 782 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.509 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     22.234 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.103 ms/op
Iteration   1: 2.175 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.422 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.859 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.972 ms/op
                 getUser·p0.999:  13.304 ms/op
                 getUser·p0.9999: 13.419 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14707
  mean =      2.175 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 11258 
    [ 2.500,  3.750) = 3081 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 9 
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
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.972 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.419 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.175 ms/op
Iteration   1: 3.201 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.280 ms/op
                 listUser·p0.99:   6.612 ms/op
                 listUser·p0.999:  15.582 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9990
  mean =      3.201 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1688 
    [ 2.500,  3.750) = 6046 
    [ 3.750,  5.000) = 2055 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.280 ms/op
     p(99.0000) =      6.612 ms/op
     p(99.9000) =     15.582 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.973          ops/ms
ClientSimple.existUser                       thrpt         13.002          ops/ms
ClientSimple.getUser                         thrpt         13.083          ops/ms
ClientSimple.listUser                        thrpt          7.684          ops/ms
ClientSimple.createUser                       avgt          2.252           ms/op
ClientSimple.existUser                        avgt          1.716           ms/op
ClientSimple.getUser                          avgt          2.150           ms/op
ClientSimple.listUser                         avgt          3.318           ms/op
ClientSimple.createUser                     sample  15587   2.050 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.668           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.866           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.675           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.510           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.308           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.656           ms/op
ClientSimple.existUser                      sample  17310   1.846 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.534           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.673           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.509           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.912           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.151           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.234           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.282           ms/op
ClientSimple.getUser                        sample  14707   2.175 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.422           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.972           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.304           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.419           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample   9990   3.201 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.788           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.916           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.280           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.612           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.582           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.514           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.514           ms/op

Benchmark result is saved to 1723637868479.json
