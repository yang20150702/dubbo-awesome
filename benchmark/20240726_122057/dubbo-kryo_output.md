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
# Warmup Iteration   1: 1.822 ops/ms
Iteration   1: 7.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.466 ops/ms


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
# Warmup Iteration   1: 5.925 ops/ms
Iteration   1: 12.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.345 ops/ms


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
# Warmup Iteration   1: 5.074 ops/ms
Iteration   1: 13.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.676 ops/ms


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
# Warmup Iteration   1: 5.232 ops/ms
Iteration   1: 8.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.094 ops/ms


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.066 ms/op
Iteration   1: 2.034 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.034 ms/op


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
# Warmup Iteration   1: 3.431 ±(99.9%) 0.054 ms/op
Iteration   1: 2.093 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.062 ms/op
Iteration   1: 1.844 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.844 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.100 ms/op
Iteration   1: 3.725 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.725 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.126 ms/op
Iteration   1: 2.349 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   8.097 ms/op
                 createUser·p0.999:  15.254 ms/op
                 createUser·p0.9999: 23.318 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13954
  mean =      2.349 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10561 
    [ 2.500,  5.000) = 3026 
    [ 5.000,  7.500) = 189 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      8.097 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     23.318 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 2.984 ±(99.9%) 0.075 ms/op
Iteration   1: 1.954 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 14.489 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16358
  mean =      1.954 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 391 
    [ 1.250,  2.500) = 14233 
    [ 2.500,  3.750) = 1560 
    [ 3.750,  5.000) = 130 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     14.489 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.094 ms/op
Iteration   1: 2.104 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.798 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  14.664 ms/op
                 getUser·p0.9999: 15.579 ms/op
                 getUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15299
  mean =      2.104 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 12886 
    [ 2.500,  3.750) = 2041 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     15.579 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.138 ms/op
Iteration   1: 4.085 ±(99.9%) 0.063 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.416 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  23.869 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7857
  mean =      4.085 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 6702 
    [ 5.000,  7.500) = 568 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.416 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     23.869 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     24.543 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.466          ops/ms
ClientSimple.existUser                       thrpt         12.345          ops/ms
ClientSimple.getUser                         thrpt         13.676          ops/ms
ClientSimple.listUser                        thrpt          8.094          ops/ms
ClientSimple.createUser                       avgt          2.034           ms/op
ClientSimple.existUser                        avgt          2.093           ms/op
ClientSimple.getUser                          avgt          1.844           ms/op
ClientSimple.listUser                         avgt          3.725           ms/op
ClientSimple.createUser                     sample  13954   2.349 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.746           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.207           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.097           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.318           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.331           ms/op
ClientSimple.existUser                      sample  16358   1.954 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.792           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.797           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.352           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.489           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.500           ms/op
ClientSimple.getUser                        sample  15299   2.104 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.536           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.117           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.805           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.664           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.579           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.761           ms/op
ClientSimple.listUser                       sample   7857   4.085 ± 0.063   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.065           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.944           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.973           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.416           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.879           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.869           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.543           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.543           ms/op

Benchmark result is saved to 1721996200161.json
