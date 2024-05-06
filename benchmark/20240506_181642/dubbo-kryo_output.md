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
# Warmup Iteration   1: 1.462 ops/ms
Iteration   1: 6.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.563 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.631 ops/ms
Iteration   1: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.067 ops/ms


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
# Warmup Iteration   1: 5.146 ops/ms
Iteration   1: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.830 ops/ms


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
# Warmup Iteration   1: 3.589 ops/ms
Iteration   1: 8.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.852 ops/ms


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.088 ms/op
Iteration   1: 2.309 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.309 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.067 ms/op
Iteration   1: 2.131 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.060 ms/op
Iteration   1: 1.788 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.788 ms/op


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.083 ms/op
Iteration   1: 3.138 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.138 ms/op


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.101 ms/op
Iteration   1: 2.139 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.325 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.589 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   5.219 ms/op
                 createUser·p0.999:  16.352 ms/op
                 createUser·p0.9999: 16.638 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14944
  mean =      2.139 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 12732 
    [ 2.500,  3.750) = 1789 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      5.219 ms/op
     p(99.9000) =     16.352 ms/op
     p(99.9900) =     16.638 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 2.880 ±(99.9%) 0.072 ms/op
Iteration   1: 1.821 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.376 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.087 ms/op
                 existUser·p0.95:   2.305 ms/op
                 existUser·p0.99:   3.438 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17585
  mean =      1.821 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 16878 
    [ 2.500,  3.750) = 424 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.087 ms/op
     p(95.0000) =      2.305 ms/op
     p(99.0000) =      3.438 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.258 ms/op
Iteration   1: 2.199 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  16.665 ms/op
                 getUser·p0.9999: 19.312 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14540
  mean =      2.199 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 257 
    [ 1.250,  2.500) = 12197 
    [ 2.500,  3.750) = 1516 
    [ 3.750,  5.000) = 194 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     16.665 ms/op
     p(99.9900) =     19.312 ms/op
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
# Warmup Iteration   1: 5.532 ±(99.9%) 0.156 ms/op
Iteration   1: 3.672 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.564 ms/op
                 listUser·p0.99:   14.153 ms/op
                 listUser·p0.999:  42.814 ms/op
                 listUser·p0.9999: 43.909 ms/op
                 listUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8716
  mean =      3.672 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8499 
    [ 5.000, 10.000) = 112 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 31 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.564 ms/op
     p(99.0000) =     14.153 ms/op
     p(99.9000) =     42.814 ms/op
     p(99.9900) =     43.909 ms/op
     p(99.9990) =     43.909 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.563          ops/ms
ClientSimple.existUser                       thrpt         13.067          ops/ms
ClientSimple.getUser                         thrpt         12.830          ops/ms
ClientSimple.listUser                        thrpt          8.852          ops/ms
ClientSimple.createUser                       avgt          2.309           ms/op
ClientSimple.existUser                        avgt          2.131           ms/op
ClientSimple.getUser                          avgt          1.788           ms/op
ClientSimple.listUser                         avgt          3.138           ms/op
ClientSimple.createUser                     sample  14944   2.139 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.325           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.219           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.352           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.638           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.646           ms/op
ClientSimple.existUser                      sample  17585   1.821 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.376           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.087           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.305           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.438           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.599           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.910           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.910           ms/op
ClientSimple.getUser                        sample  14540   2.199 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.374           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.367           ms/op
ClientSimple.getUser:getUser·p0.99          sample         10.207           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.312           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.431           ms/op
ClientSimple.listUser                       sample   8716   3.672 ± 0.096   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.948           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.564           ms/op
ClientSimple.listUser:listUser·p0.99        sample         14.153           ms/op
ClientSimple.listUser:listUser·p0.999       sample         42.814           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         43.909           ms/op
ClientSimple.listUser:listUser·p1.00        sample         43.909           ms/op

Benchmark result is saved to 1715019157878.json
