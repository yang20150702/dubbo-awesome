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
# Warmup Iteration   1: 1.120 ops/ms
Iteration   1: 3.142 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.142 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.067 ops/ms
Iteration   1: 7.615 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.615 ops/ms


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
# Warmup Iteration   1: 2.078 ops/ms
Iteration   1: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.217 ops/ms


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
# Warmup Iteration   1: 0.853 ops/ms
Iteration   1: 1.333 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.333 ops/ms


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
# Warmup Iteration   1: 16.756 ±(99.9%) 0.608 ms/op
Iteration   1: 7.534 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.534 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.165 ±(99.9%) 0.069 ms/op
Iteration   1: 2.752 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.752 ms/op


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
# Warmup Iteration   1: 7.598 ±(99.9%) 0.122 ms/op
Iteration   1: 4.338 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.338 ms/op


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
# Warmup Iteration   1: 25.707 ±(99.9%) 0.429 ms/op
Iteration   1: 17.346 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.346 ms/op


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
# Warmup Iteration   1: 10.311 ±(99.9%) 0.274 ms/op
Iteration   1: 5.317 ±(99.9%) 0.092 ms/op
                 createUser·p0.00:   1.987 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   10.469 ms/op
                 createUser·p0.99:   13.763 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 16.368 ms/op
                 createUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6013
  mean =      5.317 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 143 
    [ 2.500,  3.750) = 1260 
    [ 3.750,  5.000) = 831 
    [ 5.000,  6.250) = 3084 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =     10.469 ms/op
     p(99.0000) =     13.763 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 6.068 ±(99.9%) 0.151 ms/op
Iteration   1: 3.267 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   4.712 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  26.154 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9836
  mean =      3.267 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1278 
    [ 2.500,  5.000) = 8087 
    [ 5.000,  7.500) = 268 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      4.712 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     26.154 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 8.438 ±(99.9%) 0.299 ms/op
Iteration   1: 4.115 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   10.167 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 12.829 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7946
  mean =      4.115 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 77 
    [ 2.500,  3.750) = 3111 
    [ 3.750,  5.000) = 3907 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =     10.167 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 24.352 ±(99.9%) 0.755 ms/op
Iteration   1: 16.017 ±(99.9%) 0.260 ms/op
                 listUser·p0.00:   6.193 ms/op
                 listUser·p0.50:   15.679 ms/op
                 listUser·p0.90:   19.202 ms/op
                 listUser·p0.95:   21.996 ms/op
                 listUser·p0.99:   33.196 ms/op
                 listUser·p0.999:  38.996 ms/op
                 listUser·p0.9999: 39.387 ms/op
                 listUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1994
  mean =     16.017 ±(99.9%) 0.260 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 1109 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      6.193 ms/op
     p(50.0000) =     15.679 ms/op
     p(90.0000) =     19.202 ms/op
     p(95.0000) =     21.996 ms/op
     p(99.0000) =     33.196 ms/op
     p(99.9000) =     38.996 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     39.387 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.142          ops/ms
Client.existUser                       thrpt         7.615          ops/ms
Client.getUser                         thrpt         6.217          ops/ms
Client.listUser                        thrpt         1.333          ops/ms
Client.createUser                       avgt         7.534           ms/op
Client.existUser                        avgt         2.752           ms/op
Client.getUser                          avgt         4.338           ms/op
Client.listUser                         avgt        17.346           ms/op
Client.createUser                     sample  6013   5.317 ± 0.092   ms/op
Client.createUser:createUser·p0.00    sample         1.987           ms/op
Client.createUser:createUser·p0.50    sample         5.202           ms/op
Client.createUser:createUser·p0.90    sample         6.562           ms/op
Client.createUser:createUser·p0.95    sample        10.469           ms/op
Client.createUser:createUser·p0.99    sample        13.763           ms/op
Client.createUser:createUser·p0.999   sample        15.958           ms/op
Client.createUser:createUser·p0.9999  sample        16.368           ms/op
Client.createUser:createUser·p1.00    sample        16.368           ms/op
Client.existUser                      sample  9836   3.267 ± 0.058   ms/op
Client.existUser:existUser·p0.00      sample         0.558           ms/op
Client.existUser:existUser·p0.50      sample         3.088           ms/op
Client.existUser:existUser·p0.90      sample         3.498           ms/op
Client.existUser:existUser·p0.95      sample         4.712           ms/op
Client.existUser:existUser·p0.99      sample        10.060           ms/op
Client.existUser:existUser·p0.999     sample        26.154           ms/op
Client.existUser:existUser·p0.9999    sample        26.477           ms/op
Client.existUser:existUser·p1.00      sample        26.477           ms/op
Client.getUser                        sample  7946   4.115 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample         1.749           ms/op
Client.getUser:getUser·p0.50          sample         4.039           ms/op
Client.getUser:getUser·p0.90          sample         5.087           ms/op
Client.getUser:getUser·p0.95          sample         5.612           ms/op
Client.getUser:getUser·p0.99          sample        10.167           ms/op
Client.getUser:getUser·p0.999         sample        12.730           ms/op
Client.getUser:getUser·p0.9999        sample        12.829           ms/op
Client.getUser:getUser·p1.00          sample        12.829           ms/op
Client.listUser                       sample  1994  16.017 ± 0.260   ms/op
Client.listUser:listUser·p0.00        sample         6.193           ms/op
Client.listUser:listUser·p0.50        sample        15.679           ms/op
Client.listUser:listUser·p0.90        sample        19.202           ms/op
Client.listUser:listUser·p0.95        sample        21.996           ms/op
Client.listUser:listUser·p0.99        sample        33.196           ms/op
Client.listUser:listUser·p0.999       sample        38.996           ms/op
Client.listUser:listUser·p0.9999      sample        39.387           ms/op
Client.listUser:listUser·p1.00        sample        39.387           ms/op
