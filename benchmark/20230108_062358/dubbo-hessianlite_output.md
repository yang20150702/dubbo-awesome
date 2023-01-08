# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.414 ops/ms
Iteration   1: 1.007 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.007 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 1.223 ops/ms
Iteration   1: 3.126 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.126 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.075 ops/ms
Iteration   1: 2.125 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.125 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.565 ops/ms
Iteration   1: 0.840 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.840 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 27.280 ±(99.9%) 0.629 ms/op
Iteration   1: 17.259 ±(99.9%) 0.130 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  17.259 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 15.459 ±(99.9%) 0.218 ms/op
Iteration   1: 10.807 ±(99.9%) 0.098 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.807 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 20.122 ±(99.9%) 0.502 ms/op
Iteration   1: 10.226 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.226 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 43.807 ±(99.9%) 0.933 ms/op
Iteration   1: 30.134 ±(99.9%) 0.337 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  30.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 26.987 ±(99.9%) 0.891 ms/op
Iteration   1: 13.558 ±(99.9%) 0.476 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   13.631 ms/op
                 createUser·p0.90:   20.631 ms/op
                 createUser·p0.95:   26.028 ms/op
                 createUser·p0.99:   41.449 ms/op
                 createUser·p0.999:  51.750 ms/op
                 createUser·p0.9999: 54.657 ms/op
                 createUser·p1.00:   54.657 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2353
  mean =     13.558 ±(99.9%) 0.476 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66 
    [ 5.000, 10.000) = 694 
    [10.000, 15.000) = 908 
    [15.000, 20.000) = 434 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 65 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 44 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.429 ms/op
     p(50.0000) =     13.631 ms/op
     p(90.0000) =     20.631 ms/op
     p(95.0000) =     26.028 ms/op
     p(99.0000) =     41.449 ms/op
     p(99.9000) =     51.750 ms/op
     p(99.9900) =     54.657 ms/op
     p(99.9990) =     54.657 ms/op
     p(99.9999) =     54.657 ms/op
    p(100.0000) =     54.657 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.592 ±(99.9%) 0.291 ms/op
Iteration   1: 8.280 ±(99.9%) 0.181 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   8.077 ms/op
                 existUser·p0.90:   11.433 ms/op
                 existUser·p0.95:   13.517 ms/op
                 existUser·p0.99:   23.822 ms/op
                 existUser·p0.999:  25.665 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3881
  mean =      8.280 ±(99.9%) 0.181 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 491 
    [ 5.000,  7.500) = 1213 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      8.077 ms/op
     p(90.0000) =     11.433 ms/op
     p(95.0000) =     13.517 ms/op
     p(99.0000) =     23.822 ms/op
     p(99.9000) =     25.665 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 19.815 ±(99.9%) 0.879 ms/op
Iteration   1: 9.315 ±(99.9%) 0.301 ms/op
                 getUser·p0.00:   2.638 ms/op
                 getUser·p0.50:   7.332 ms/op
                 getUser·p0.90:   14.467 ms/op
                 getUser·p0.95:   16.728 ms/op
                 getUser·p0.99:   28.908 ms/op
                 getUser·p0.999:  53.019 ms/op
                 getUser·p0.9999: 53.150 ms/op
                 getUser·p1.00:   53.150 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3428
  mean =      9.315 ±(99.9%) 0.301 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 54 
    [ 5.000, 10.000) = 2338 
    [10.000, 15.000) = 741 
    [15.000, 20.000) = 196 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 9 
    [50.000, 55.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.638 ms/op
     p(50.0000) =      7.332 ms/op
     p(90.0000) =     14.467 ms/op
     p(95.0000) =     16.728 ms/op
     p(99.0000) =     28.908 ms/op
     p(99.9000) =     53.019 ms/op
     p(99.9900) =     53.150 ms/op
     p(99.9990) =     53.150 ms/op
     p(99.9999) =     53.150 ms/op
    p(100.0000) =     53.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 53.540 ±(99.9%) 2.786 ms/op
Iteration   1: 30.022 ±(99.9%) 0.783 ms/op
                 listUser·p0.00:   12.435 ms/op
                 listUser·p0.50:   27.984 ms/op
                 listUser·p0.90:   39.322 ms/op
                 listUser·p0.95:   47.717 ms/op
                 listUser·p0.99:   60.849 ms/op
                 listUser·p0.999:  78.354 ms/op
                 listUser·p0.9999: 78.381 ms/op
                 listUser·p1.00:   78.381 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1068
  mean =     30.022 ±(99.9%) 0.783 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 18 
    [20.000, 25.000) = 107 
    [25.000, 30.000) = 668 
    [30.000, 35.000) = 105 
    [35.000, 40.000) = 72 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 56 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 9 
    [60.000, 65.000) = 6 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =     12.435 ms/op
     p(50.0000) =     27.984 ms/op
     p(90.0000) =     39.322 ms/op
     p(95.0000) =     47.717 ms/op
     p(99.0000) =     60.849 ms/op
     p(99.9000) =     78.354 ms/op
     p(99.9900) =     78.381 ms/op
     p(99.9990) =     78.381 ms/op
     p(99.9999) =     78.381 ms/op
    p(100.0000) =     78.381 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.007          ops/ms
Client.existUser                       thrpt         3.126          ops/ms
Client.getUser                         thrpt         2.125          ops/ms
Client.listUser                        thrpt         0.840          ops/ms
Client.createUser                       avgt        17.259           ms/op
Client.existUser                        avgt        10.807           ms/op
Client.getUser                          avgt        10.226           ms/op
Client.listUser                         avgt        30.134           ms/op
Client.createUser                     sample  2353  13.558 ± 0.476   ms/op
Client.createUser:createUser·p0.00    sample         2.429           ms/op
Client.createUser:createUser·p0.50    sample        13.631           ms/op
Client.createUser:createUser·p0.90    sample        20.631           ms/op
Client.createUser:createUser·p0.95    sample        26.028           ms/op
Client.createUser:createUser·p0.99    sample        41.449           ms/op
Client.createUser:createUser·p0.999   sample        51.750           ms/op
Client.createUser:createUser·p0.9999  sample        54.657           ms/op
Client.createUser:createUser·p1.00    sample        54.657           ms/op
Client.existUser                      sample  3881   8.280 ± 0.181   ms/op
Client.existUser:existUser·p0.00      sample         1.739           ms/op
Client.existUser:existUser·p0.50      sample         8.077           ms/op
Client.existUser:existUser·p0.90      sample        11.433           ms/op
Client.existUser:existUser·p0.95      sample        13.517           ms/op
Client.existUser:existUser·p0.99      sample        23.822           ms/op
Client.existUser:existUser·p0.999     sample        25.665           ms/op
Client.existUser:existUser·p0.9999    sample        25.854           ms/op
Client.existUser:existUser·p1.00      sample        25.854           ms/op
Client.getUser                        sample  3428   9.315 ± 0.301   ms/op
Client.getUser:getUser·p0.00          sample         2.638           ms/op
Client.getUser:getUser·p0.50          sample         7.332           ms/op
Client.getUser:getUser·p0.90          sample        14.467           ms/op
Client.getUser:getUser·p0.95          sample        16.728           ms/op
Client.getUser:getUser·p0.99          sample        28.908           ms/op
Client.getUser:getUser·p0.999         sample        53.019           ms/op
Client.getUser:getUser·p0.9999        sample        53.150           ms/op
Client.getUser:getUser·p1.00          sample        53.150           ms/op
Client.listUser                       sample  1068  30.022 ± 0.783   ms/op
Client.listUser:listUser·p0.00        sample        12.435           ms/op
Client.listUser:listUser·p0.50        sample        27.984           ms/op
Client.listUser:listUser·p0.90        sample        39.322           ms/op
Client.listUser:listUser·p0.95        sample        47.717           ms/op
Client.listUser:listUser·p0.99        sample        60.849           ms/op
Client.listUser:listUser·p0.999       sample        78.354           ms/op
Client.listUser:listUser·p0.9999      sample        78.381           ms/op
Client.listUser:listUser·p1.00        sample        78.381           ms/op
