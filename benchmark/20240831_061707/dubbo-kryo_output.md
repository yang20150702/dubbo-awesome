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
# Warmup Iteration   1: 1.239 ops/ms
Iteration   1: 7.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.179 ops/ms


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
# Warmup Iteration   1: 5.949 ops/ms
Iteration   1: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.128 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.929 ops/ms
Iteration   1: 13.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.236 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
Iteration   1: 7.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.940 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.072 ms/op
Iteration   1: 2.157 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.157 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.062 ms/op
Iteration   1: 1.801 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.801 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.063 ms/op
Iteration   1: 2.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.097 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.083 ms/op
Iteration   1: 3.457 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.457 ms/op


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
# Warmup Iteration   1: 3.535 ±(99.9%) 0.092 ms/op
Iteration   1: 2.156 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   8.891 ms/op
                 createUser·p0.999:  14.811 ms/op
                 createUser·p0.9999: 17.434 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14835
  mean =      2.156 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 528 
    [ 1.250,  2.500) = 12458 
    [ 2.500,  3.750) = 1467 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      8.891 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     17.434 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.081 ms/op
Iteration   1: 1.886 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.395 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 14.791 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17048
  mean =      1.886 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 743 
    [ 1.250,  2.500) = 15455 
    [ 2.500,  3.750) = 690 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     14.791 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.200 ±(99.9%) 0.076 ms/op
Iteration   1: 1.792 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.679 ms/op
                 getUser·p0.90:   2.277 ms/op
                 getUser·p0.95:   2.454 ms/op
                 getUser·p0.99:   3.136 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 14.969 ms/op
                 getUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17966
  mean =      1.792 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 385 
    [ 1.250,  2.500) = 16806 
    [ 2.500,  3.750) = 684 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.136 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     14.969 ms/op
     p(99.9990) =     15.073 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.144 ms/op
Iteration   1: 3.384 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.107 ms/op
                 listUser·p0.999:  6.959 ms/op
                 listUser·p0.9999: 9.142 ms/op
                 listUser·p1.00:   9.142 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9454
  mean =      3.384 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 118 
    [ 2.000,  3.000) = 2238 
    [ 3.000,  4.000) = 6112 
    [ 4.000,  5.000) = 792 
    [ 5.000,  6.000) = 81 
    [ 6.000,  7.000) = 104 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.107 ms/op
     p(99.9000) =      6.959 ms/op
     p(99.9900) =      9.142 ms/op
     p(99.9990) =      9.142 ms/op
     p(99.9999) =      9.142 ms/op
    p(100.0000) =      9.142 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.179          ops/ms
ClientSimple.existUser                       thrpt         13.128          ops/ms
ClientSimple.getUser                         thrpt         13.236          ops/ms
ClientSimple.listUser                        thrpt          7.940          ops/ms
ClientSimple.createUser                       avgt          2.157           ms/op
ClientSimple.existUser                        avgt          1.801           ms/op
ClientSimple.getUser                          avgt          2.097           ms/op
ClientSimple.listUser                         avgt          3.457           ms/op
ClientSimple.createUser                     sample  14835   2.156 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.557           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.891           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.811           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.434           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.465           ms/op
ClientSimple.existUser                      sample  17048   1.886 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.395           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.812           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.453           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.189           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.791           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.860           ms/op
ClientSimple.getUser                        sample  17966   1.792 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.679           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.136           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.713           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.969           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.073           ms/op
ClientSimple.listUser                       sample   9454   3.384 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.985           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.107           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.959           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.142           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.142           ms/op

Benchmark result is saved to 1725084771252.json
