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
# Warmup Iteration   1: 1.848 ops/ms
Iteration   1: 6.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.993 ops/ms


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
# Warmup Iteration   1: 5.275 ops/ms
Iteration   1: 12.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.137 ops/ms


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
# Warmup Iteration   1: 5.144 ops/ms
Iteration   1: 12.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.135 ops/ms


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
# Warmup Iteration   1: 5.501 ops/ms
Iteration   1: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.615 ops/ms


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.071 ms/op
Iteration   1: 2.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.083 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.054 ms/op
Iteration   1: 2.081 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.081 ms/op


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
# Warmup Iteration   1: 3.503 ±(99.9%) 0.051 ms/op
Iteration   1: 2.029 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.029 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.096 ms/op
Iteration   1: 3.129 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.129 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.114 ms/op
Iteration   1: 2.149 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.826 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   4.281 ms/op
                 createUser·p0.999:  15.343 ms/op
                 createUser·p0.9999: 15.822 ms/op
                 createUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14846
  mean =      2.149 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 10593 
    [ 2.500,  3.750) = 3886 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.281 ms/op
     p(99.9000) =     15.343 ms/op
     p(99.9900) =     15.822 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.065 ms/op
Iteration   1: 1.866 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.203 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.773 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 22.802 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17150
  mean =      1.866 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16622 
    [ 2.500,  5.000) = 400 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.203 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.773 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     22.802 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ±(99.9%) 0.072 ms/op
Iteration   1: 2.097 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   2.013 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   3.420 ms/op
                 getUser·p0.999:  17.924 ms/op
                 getUser·p0.9999: 18.181 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15252
  mean =      2.097 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 12417 
    [ 2.500,  3.750) = 2515 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      3.420 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     18.181 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.143 ms/op
Iteration   1: 3.130 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  16.194 ms/op
                 listUser·p0.9999: 17.821 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10199
  mean =      3.130 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 769 
    [ 2.500,  3.750) = 8335 
    [ 3.750,  5.000) = 961 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     16.194 ms/op
     p(99.9900) =     17.821 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.993          ops/ms
ClientSimple.existUser                       thrpt         12.137          ops/ms
ClientSimple.getUser                         thrpt         12.135          ops/ms
ClientSimple.listUser                        thrpt          8.615          ops/ms
ClientSimple.createUser                       avgt          2.083           ms/op
ClientSimple.existUser                        avgt          2.081           ms/op
ClientSimple.getUser                          avgt          2.029           ms/op
ClientSimple.listUser                         avgt          3.129           ms/op
ClientSimple.createUser                     sample  14846   2.149 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.688           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.281           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.343           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.822           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.909           ms/op
ClientSimple.existUser                      sample  17150   1.866 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.746           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.203           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.773           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.053           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.802           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.872           ms/op
ClientSimple.getUser                        sample  15252   2.097 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.602           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.013           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.420           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.924           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.181           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.285           ms/op
ClientSimple.listUser                       sample  10199   3.130 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.798           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.990           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.121           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.374           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.194           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.821           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.826           ms/op

Benchmark result is saved to 1722406308439.json
