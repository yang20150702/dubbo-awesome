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
# Warmup Iteration   1: 0.853 ops/ms
Iteration   1: 2.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.365 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.947 ops/ms
Iteration   1: 5.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.606 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.426 ops/ms
Iteration   1: 6.522 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.522 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.864 ops/ms
Iteration   1: 1.498 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.498 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 13.803 ±(99.9%) 0.243 ms/op
Iteration   1: 7.184 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.184 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ±(99.9%) 0.091 ms/op
Iteration   1: 3.416 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.416 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.170 ±(99.9%) 0.120 ms/op
Iteration   1: 4.638 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.638 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 30.097 ±(99.9%) 0.519 ms/op
Iteration   1: 15.375 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.375 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.855 ±(99.9%) 0.361 ms/op
Iteration   1: 6.170 ±(99.9%) 0.107 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.644 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   10.420 ms/op
                 createUser·p0.99:   17.662 ms/op
                 createUser·p0.999:  23.749 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5227
  mean =      6.170 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 352 
    [ 5.000,  7.500) = 4401 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.429 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =     10.420 ms/op
     p(99.0000) =     17.662 ms/op
     p(99.9000) =     23.749 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 7.151 ±(99.9%) 0.218 ms/op
Iteration   1: 3.501 ±(99.9%) 0.065 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.623 ms/op
                 existUser·p0.99:   11.715 ms/op
                 existUser·p0.999:  24.957 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9377
  mean =      3.501 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 836 
    [ 2.500,  5.000) = 8112 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.623 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     24.957 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 7.490 ±(99.9%) 0.247 ms/op
Iteration   1: 4.478 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   8.285 ms/op
                 getUser·p0.999:  19.434 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7152
  mean =      4.478 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 5965 
    [ 5.000,  7.500) = 1066 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.285 ms/op
     p(99.9000) =     19.434 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 28.841 ±(99.9%) 1.069 ms/op
Iteration   1: 16.092 ±(99.9%) 0.186 ms/op
                 listUser·p0.00:   5.710 ms/op
                 listUser·p0.50:   15.942 ms/op
                 listUser·p0.90:   18.606 ms/op
                 listUser·p0.95:   19.792 ms/op
                 listUser·p0.99:   28.502 ms/op
                 listUser·p0.999:  36.044 ms/op
                 listUser·p0.9999: 38.076 ms/op
                 listUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2000
  mean =     16.092 ±(99.9%) 0.186 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 499 
    [15.000, 17.500) = 1152 
    [17.500, 20.000) = 196 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.710 ms/op
     p(50.0000) =     15.942 ms/op
     p(90.0000) =     18.606 ms/op
     p(95.0000) =     19.792 ms/op
     p(99.0000) =     28.502 ms/op
     p(99.9000) =     36.044 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.365          ops/ms
Client.existUser                       thrpt         5.606          ops/ms
Client.getUser                         thrpt         6.522          ops/ms
Client.listUser                        thrpt         1.498          ops/ms
Client.createUser                       avgt         7.184           ms/op
Client.existUser                        avgt         3.416           ms/op
Client.getUser                          avgt         4.638           ms/op
Client.listUser                         avgt        15.375           ms/op
Client.createUser                     sample  5227   6.170 ± 0.107   ms/op
Client.createUser:createUser·p0.00    sample         2.429           ms/op
Client.createUser:createUser·p0.50    sample         5.644           ms/op
Client.createUser:createUser·p0.90    sample         6.496           ms/op
Client.createUser:createUser·p0.95    sample        10.420           ms/op
Client.createUser:createUser·p0.99    sample        17.662           ms/op
Client.createUser:createUser·p0.999   sample        23.749           ms/op
Client.createUser:createUser·p0.9999  sample        24.084           ms/op
Client.createUser:createUser·p1.00    sample        24.084           ms/op
Client.existUser                      sample  9377   3.501 ± 0.065   ms/op
Client.existUser:existUser·p0.00      sample         0.893           ms/op
Client.existUser:existUser·p0.50      sample         3.047           ms/op
Client.existUser:existUser·p0.90      sample         3.871           ms/op
Client.existUser:existUser·p0.95      sample         4.623           ms/op
Client.existUser:existUser·p0.99      sample        11.715           ms/op
Client.existUser:existUser·p0.999     sample        24.957           ms/op
Client.existUser:existUser·p0.9999    sample        25.330           ms/op
Client.existUser:existUser·p1.00      sample        25.330           ms/op
Client.getUser                        sample  7152   4.478 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample         1.450           ms/op
Client.getUser:getUser·p0.50          sample         4.309           ms/op
Client.getUser:getUser·p0.90          sample         5.210           ms/op
Client.getUser:getUser·p0.95          sample         5.554           ms/op
Client.getUser:getUser·p0.99          sample         8.285           ms/op
Client.getUser:getUser·p0.999         sample        19.434           ms/op
Client.getUser:getUser·p0.9999        sample        20.414           ms/op
Client.getUser:getUser·p1.00          sample        20.414           ms/op
Client.listUser                       sample  2000  16.092 ± 0.186   ms/op
Client.listUser:listUser·p0.00        sample         5.710           ms/op
Client.listUser:listUser·p0.50        sample        15.942           ms/op
Client.listUser:listUser·p0.90        sample        18.606           ms/op
Client.listUser:listUser·p0.95        sample        19.792           ms/op
Client.listUser:listUser·p0.99        sample        28.502           ms/op
Client.listUser:listUser·p0.999       sample        36.044           ms/op
Client.listUser:listUser·p0.9999      sample        38.076           ms/op
Client.listUser:listUser·p1.00        sample        38.076           ms/op
