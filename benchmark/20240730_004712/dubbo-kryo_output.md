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
# Warmup Iteration   1: 1.837 ops/ms
Iteration   1: 5.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.885 ops/ms


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
# Warmup Iteration   1: 6.715 ops/ms
Iteration   1: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.989 ops/ms


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
# Warmup Iteration   1: 5.805 ops/ms
Iteration   1: 14.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.001 ops/ms


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
# Warmup Iteration   1: 5.278 ops/ms
Iteration   1: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.019 ops/ms


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.058 ms/op
Iteration   1: 2.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.098 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.066 ms/op
Iteration   1: 1.947 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.072 ms/op
Iteration   1: 2.178 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.178 ms/op


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.099 ms/op
Iteration   1: 4.077 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.077 ms/op


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.100 ms/op
Iteration   1: 2.090 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   1.999 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   4.630 ms/op
                 createUser·p0.999:  14.615 ms/op
                 createUser·p0.9999: 14.941 ms/op
                 createUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15277
  mean =      2.090 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 13434 
    [ 2.500,  3.750) = 1322 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      4.630 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     14.941 ms/op
     p(99.9990) =     14.959 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.063 ms/op
Iteration   1: 2.007 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.568 ms/op
                 existUser·p0.95:   2.786 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  14.336 ms/op
                 existUser·p0.9999: 14.500 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15914
  mean =      2.007 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 871 
    [ 1.250,  2.500) = 12976 
    [ 2.500,  3.750) = 1951 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.786 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     14.500 ms/op
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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.086 ms/op
Iteration   1: 1.966 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   1.792 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.929 ms/op
                 getUser·p0.99:   3.445 ms/op
                 getUser·p0.999:  12.122 ms/op
                 getUser·p0.9999: 12.724 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16262
  mean =      1.966 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 508 
    [ 1.250,  2.500) = 12587 
    [ 2.500,  3.750) = 3047 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      3.445 ms/op
     p(99.9000) =     12.122 ms/op
     p(99.9900) =     12.724 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.138 ms/op
Iteration   1: 3.059 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.810 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.668 ms/op
                 listUser·p0.999:  10.479 ms/op
                 listUser·p0.9999: 10.742 ms/op
                 listUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10435
  mean =      3.059 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 90 
    [ 2.000,  3.000) = 6890 
    [ 3.000,  4.000) = 2520 
    [ 4.000,  5.000) = 765 
    [ 5.000,  6.000) = 92 
    [ 6.000,  7.000) = 44 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.668 ms/op
     p(99.9000) =     10.479 ms/op
     p(99.9900) =     10.742 ms/op
     p(99.9990) =     10.748 ms/op
     p(99.9999) =     10.748 ms/op
    p(100.0000) =     10.748 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.885          ops/ms
ClientSimple.existUser                       thrpt         12.989          ops/ms
ClientSimple.getUser                         thrpt         14.001          ops/ms
ClientSimple.listUser                        thrpt          9.019          ops/ms
ClientSimple.createUser                       avgt          2.098           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          2.178           ms/op
ClientSimple.listUser                         avgt          4.077           ms/op
ClientSimple.createUser                     sample  15277   2.090 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.536           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.999           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.630           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.615           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.959           ms/op
ClientSimple.existUser                      sample  15914   2.007 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.468           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.909           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.786           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.379           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.336           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.500           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.500           ms/op
ClientSimple.getUser                        sample  16262   1.966 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.640           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.792           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.445           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.122           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.724           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample  10435   3.059 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.942           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.810           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.912           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.479           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.742           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.748           ms/op

Benchmark result is saved to 1722300170064.json
