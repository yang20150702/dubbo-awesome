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
# Warmup Iteration   1: 1.747 ops/ms
Iteration   1: 6.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.598 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.993 ops/ms
Iteration   1: 11.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.583 ops/ms


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
# Warmup Iteration   1: 5.868 ops/ms
Iteration   1: 12.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.395 ops/ms


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
# Warmup Iteration   1: 4.478 ops/ms
Iteration   1: 8.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.972 ops/ms


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.088 ms/op
Iteration   1: 2.159 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.048 ms/op
Iteration   1: 1.977 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.977 ms/op


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
# Warmup Iteration   1: 3.396 ±(99.9%) 0.055 ms/op
Iteration   1: 2.018 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.018 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.075 ms/op
Iteration   1: 4.032 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.032 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.103 ms/op
Iteration   1: 2.120 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   1.841 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.885 ms/op
                 createUser·p0.99:   9.404 ms/op
                 createUser·p0.999:  28.725 ms/op
                 createUser·p0.9999: 30.094 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15194
  mean =      2.120 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13596 
    [ 2.500,  5.000) = 1342 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.885 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     28.725 ms/op
     p(99.9900) =     30.094 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.082 ms/op
Iteration   1: 1.938 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   1.812 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 10.084 ms/op
                 existUser·p1.00:   10.224 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16573
  mean =      1.938 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 52 
    [ 1.000,  2.000) = 10564 
    [ 2.000,  3.000) = 5455 
    [ 3.000,  4.000) = 394 
    [ 4.000,  5.000) = 57 
    [ 5.000,  6.000) = 19 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     10.084 ms/op
     p(99.9990) =     10.224 ms/op
     p(99.9999) =     10.224 ms/op
    p(100.0000) =     10.224 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.108 ms/op
Iteration   1: 2.160 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   3.718 ms/op
                 getUser·p0.999:  16.687 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14821
  mean =      2.160 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 11672 
    [ 2.500,  3.750) = 2814 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.718 ms/op
     p(99.9000) =     16.687 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.145 ms/op
Iteration   1: 3.485 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.305 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  23.527 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9173
  mean =      3.485 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 848 
    [ 2.500,  5.000) = 8014 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     23.527 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.598          ops/ms
ClientSimple.existUser                       thrpt         11.583          ops/ms
ClientSimple.getUser                         thrpt         12.395          ops/ms
ClientSimple.listUser                        thrpt          8.972          ops/ms
ClientSimple.createUser                       avgt          2.159           ms/op
ClientSimple.existUser                        avgt          1.977           ms/op
ClientSimple.getUser                          avgt          2.018           ms/op
ClientSimple.listUser                         avgt          4.032           ms/op
ClientSimple.createUser                     sample  15194   2.120 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.524           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.841           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.885           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.404           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.725           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.094           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.179           ms/op
ClientSimple.existUser                      sample  16573   1.938 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.628           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.812           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.654           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.765           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.084           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.224           ms/op
ClientSimple.getUser                        sample  14821   2.160 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.700           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.718           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.687           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.105           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.105           ms/op
ClientSimple.listUser                       sample   9173   3.485 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.511           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.305           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.824           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.527           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.593           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.593           ms/op

Benchmark result is saved to 1723918334359.json
