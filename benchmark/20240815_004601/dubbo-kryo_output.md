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
# Warmup Iteration   1: 1.840 ops/ms
Iteration   1: 6.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.780 ops/ms


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
# Warmup Iteration   1: 6.566 ops/ms
Iteration   1: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.077 ops/ms


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
# Warmup Iteration   1: 5.857 ops/ms
Iteration   1: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.661 ops/ms


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
# Warmup Iteration   1: 3.709 ops/ms
Iteration   1: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.787 ops/ms


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.073 ms/op
Iteration   1: 2.722 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.722 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.052 ms/op
Iteration   1: 1.934 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.934 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.069 ms/op
Iteration   1: 2.312 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.312 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.097 ms/op
Iteration   1: 3.612 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.612 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.114 ms/op
Iteration   1: 2.262 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.843 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   8.449 ms/op
                 createUser·p0.999:  15.173 ms/op
                 createUser·p0.9999: 16.291 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14131
  mean =      2.262 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 10855 
    [ 2.500,  3.750) = 2588 
    [ 3.750,  5.000) = 212 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 110 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      8.449 ms/op
     p(99.9000) =     15.173 ms/op
     p(99.9900) =     16.291 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.074 ±(99.9%) 0.071 ms/op
Iteration   1: 1.816 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.031 ms/op
                 existUser·p0.999:  14.816 ms/op
                 existUser·p0.9999: 15.478 ms/op
                 existUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17677
  mean =      1.816 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 16789 
    [ 2.500,  3.750) = 616 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.031 ms/op
     p(99.9000) =     14.816 ms/op
     p(99.9900) =     15.478 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.084 ms/op
Iteration   1: 1.935 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   3.482 ms/op
                 getUser·p0.999:  16.646 ms/op
                 getUser·p0.9999: 17.784 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16523
  mean =      1.935 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 14950 
    [ 2.500,  3.750) = 1412 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     17.784 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.990 ±(99.9%) 0.120 ms/op
Iteration   1: 3.821 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  20.627 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8380
  mean =      3.821 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 391 
    [ 2.500,  5.000) = 7538 
    [ 5.000,  7.500) = 419 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     20.627 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.780          ops/ms
ClientSimple.existUser                       thrpt         13.077          ops/ms
ClientSimple.getUser                         thrpt         12.661          ops/ms
ClientSimple.listUser                        thrpt          8.787          ops/ms
ClientSimple.createUser                       avgt          2.722           ms/op
ClientSimple.existUser                        avgt          1.934           ms/op
ClientSimple.getUser                          avgt          2.312           ms/op
ClientSimple.listUser                         avgt          3.612           ms/op
ClientSimple.createUser                     sample  14131   2.262 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.519           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.449           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.173           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.291           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.318           ms/op
ClientSimple.existUser                      sample  17677   1.816 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.514           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.031           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.816           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.478           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.516           ms/op
ClientSimple.getUser                        sample  16523   1.935 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.864           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.482           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.646           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.784           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.891           ms/op
ClientSimple.listUser                       sample   8380   3.821 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.900           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.727           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.627           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.168           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.168           ms/op

Benchmark result is saved to 1723682507139.json
