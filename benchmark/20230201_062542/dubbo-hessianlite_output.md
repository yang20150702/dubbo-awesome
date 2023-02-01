# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.982 ops/ms
Iteration   1: 2.361 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.361 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
Iteration   1: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.161 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.299 ops/ms
Iteration   1: 4.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.597 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.753 ops/ms
Iteration   1: 1.317 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.317 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 21.409 ±(99.9%) 0.369 ms/op
Iteration   1: 9.859 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.677 ±(99.9%) 0.143 ms/op
Iteration   1: 5.103 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.079 ±(99.9%) 0.221 ms/op
Iteration   1: 5.265 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.265 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 28.310 ±(99.9%) 0.683 ms/op
Iteration   1: 17.733 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.733 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.286 ±(99.9%) 0.313 ms/op
Iteration   1: 5.562 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   5.898 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   7.727 ms/op
                 createUser·p0.99:   17.927 ms/op
                 createUser·p0.999:  30.881 ms/op
                 createUser·p0.9999: 31.261 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5795
  mean =      5.562 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 2322 
    [ 5.000,  7.500) = 3135 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.727 ms/op
     p(99.0000) =     17.927 ms/op
     p(99.9000) =     30.881 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.600 ±(99.9%) 0.226 ms/op
Iteration   1: 4.565 ±(99.9%) 0.096 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   8.159 ms/op
                 existUser·p0.99:   14.352 ms/op
                 existUser·p0.999:  22.772 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7008
  mean =      4.565 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 5339 
    [ 5.000,  7.500) = 863 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     14.352 ms/op
     p(99.9000) =     22.772 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.733 ±(99.9%) 0.347 ms/op
Iteration   1: 4.833 ±(99.9%) 0.111 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   7.619 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   11.406 ms/op
                 getUser·p0.999:  31.849 ms/op
                 getUser·p0.9999: 37.683 ms/op
                 getUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6720
  mean =      4.833 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 4845 
    [ 5.000,  7.500) = 976 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     11.406 ms/op
     p(99.9000) =     31.849 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.493 ±(99.9%) 0.922 ms/op
Iteration   1: 16.868 ±(99.9%) 0.341 ms/op
                 listUser·p0.00:   4.596 ms/op
                 listUser·p0.50:   15.319 ms/op
                 listUser·p0.90:   20.546 ms/op
                 listUser·p0.95:   25.716 ms/op
                 listUser·p0.99:   34.406 ms/op
                 listUser·p0.999:  39.139 ms/op
                 listUser·p0.9999: 39.256 ms/op
                 listUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1891
  mean =     16.868 ±(99.9%) 0.341 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 701 
    [15.000, 17.500) = 404 
    [17.500, 20.000) = 473 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.596 ms/op
     p(50.0000) =     15.319 ms/op
     p(90.0000) =     20.546 ms/op
     p(95.0000) =     25.716 ms/op
     p(99.0000) =     34.406 ms/op
     p(99.9000) =     39.139 ms/op
     p(99.9900) =     39.256 ms/op
     p(99.9990) =     39.256 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.361          ops/ms
Client.existUser                       thrpt         6.161          ops/ms
Client.getUser                         thrpt         4.597          ops/ms
Client.listUser                        thrpt         1.317          ops/ms
Client.createUser                       avgt         9.859           ms/op
Client.existUser                        avgt         5.103           ms/op
Client.getUser                          avgt         5.265           ms/op
Client.listUser                         avgt        17.733           ms/op
Client.createUser                     sample  5795   5.562 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample         2.171           ms/op
Client.createUser:createUser·p0.50    sample         5.898           ms/op
Client.createUser:createUser·p0.90    sample         6.660           ms/op
Client.createUser:createUser·p0.95    sample         7.727           ms/op
Client.createUser:createUser·p0.99    sample        17.927           ms/op
Client.createUser:createUser·p0.999   sample        30.881           ms/op
Client.createUser:createUser·p0.9999  sample        31.261           ms/op
Client.createUser:createUser·p1.00    sample        31.261           ms/op
Client.existUser                      sample  7008   4.565 ± 0.096   ms/op
Client.existUser:existUser·p0.00      sample         1.577           ms/op
Client.existUser:existUser·p0.50      sample         4.342           ms/op
Client.existUser:existUser·p0.90      sample         5.554           ms/op
Client.existUser:existUser·p0.95      sample         8.159           ms/op
Client.existUser:existUser·p0.99      sample        14.352           ms/op
Client.existUser:existUser·p0.999     sample        22.772           ms/op
Client.existUser:existUser·p0.9999    sample        24.281           ms/op
Client.existUser:existUser·p1.00      sample        24.281           ms/op
Client.getUser                        sample  6720   4.833 ± 0.111   ms/op
Client.getUser:getUser·p0.00          sample         1.028           ms/op
Client.getUser:getUser·p0.50          sample         3.928           ms/op
Client.getUser:getUser·p0.90          sample         7.619           ms/op
Client.getUser:getUser·p0.95          sample         8.372           ms/op
Client.getUser:getUser·p0.99          sample        11.406           ms/op
Client.getUser:getUser·p0.999         sample        31.849           ms/op
Client.getUser:getUser·p0.9999        sample        37.683           ms/op
Client.getUser:getUser·p1.00          sample        37.683           ms/op
Client.listUser                       sample  1891  16.868 ± 0.341   ms/op
Client.listUser:listUser·p0.00        sample         4.596           ms/op
Client.listUser:listUser·p0.50        sample        15.319           ms/op
Client.listUser:listUser·p0.90        sample        20.546           ms/op
Client.listUser:listUser·p0.95        sample        25.716           ms/op
Client.listUser:listUser·p0.99        sample        34.406           ms/op
Client.listUser:listUser·p0.999       sample        39.139           ms/op
Client.listUser:listUser·p0.9999      sample        39.256           ms/op
Client.listUser:listUser·p1.00        sample        39.256           ms/op
