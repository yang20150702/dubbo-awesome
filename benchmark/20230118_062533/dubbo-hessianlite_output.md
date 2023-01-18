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
# Warmup Iteration   1: 0.676 ops/ms
Iteration   1: 1.128 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.128 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 1.365 ops/ms
Iteration   1: 2.956 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.956 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.070 ops/ms
Iteration   1: 2.009 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.009 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.562 ops/ms
Iteration   1: 0.811 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.811 ops/ms


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
# Warmup Iteration   1: 27.270 ±(99.9%) 0.620 ms/op
Iteration   1: 13.945 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.945 ms/op


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
# Warmup Iteration   1: 17.889 ±(99.9%) 0.505 ms/op
Iteration   1: 10.000 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.000 ms/op


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
# Warmup Iteration   1: 27.247 ±(99.9%) 0.598 ms/op
Iteration   1: 10.902 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.902 ms/op


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
# Warmup Iteration   1: 41.354 ±(99.9%) 0.980 ms/op
Iteration   1: 27.027 ±(99.9%) 0.313 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.027 ms/op


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
# Warmup Iteration   1: 22.907 ±(99.9%) 1.050 ms/op
Iteration   1: 11.918 ±(99.9%) 0.352 ms/op
                 createUser·p0.00:   7.234 ms/op
                 createUser·p0.50:   9.945 ms/op
                 createUser·p0.90:   16.730 ms/op
                 createUser·p0.95:   23.283 ms/op
                 createUser·p0.99:   40.829 ms/op
                 createUser·p0.999:  42.336 ms/op
                 createUser·p0.9999: 42.467 ms/op
                 createUser·p1.00:   42.467 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2768
  mean =     11.918 ±(99.9%) 0.352 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 1466 
    [10.000, 15.000) = 971 
    [15.000, 20.000) = 167 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 27 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 52 

  Percentiles, ms/op:
      p(0.0000) =      7.234 ms/op
     p(50.0000) =      9.945 ms/op
     p(90.0000) =     16.730 ms/op
     p(95.0000) =     23.283 ms/op
     p(99.0000) =     40.829 ms/op
     p(99.9000) =     42.336 ms/op
     p(99.9900) =     42.467 ms/op
     p(99.9990) =     42.467 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


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
# Warmup Iteration   1: 14.073 ±(99.9%) 0.567 ms/op
Iteration   1: 7.294 ±(99.9%) 0.149 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   7.037 ms/op
                 existUser·p0.90:   9.437 ms/op
                 existUser·p0.95:   11.583 ms/op
                 existUser·p0.99:   22.318 ms/op
                 existUser·p0.999:  25.461 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4395
  mean =      7.294 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 300 
    [ 5.000,  7.500) = 2508 
    [ 7.500, 10.000) = 1113 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      7.037 ms/op
     p(90.0000) =      9.437 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     22.318 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 22.683 ±(99.9%) 0.931 ms/op
Iteration   1: 8.285 ±(99.9%) 0.189 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   7.627 ms/op
                 getUser·p0.90:   10.817 ms/op
                 getUser·p0.95:   14.772 ms/op
                 getUser·p0.99:   21.713 ms/op
                 getUser·p0.999:  39.332 ms/op
                 getUser·p0.9999: 40.305 ms/op
                 getUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3837
  mean =      8.285 ±(99.9%) 0.189 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 156 
    [ 5.000, 10.000) = 3176 
    [10.000, 15.000) = 319 
    [15.000, 20.000) = 120 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      7.627 ms/op
     p(90.0000) =     10.817 ms/op
     p(95.0000) =     14.772 ms/op
     p(99.0000) =     21.713 ms/op
     p(99.9000) =     39.332 ms/op
     p(99.9900) =     40.305 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


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
# Warmup Iteration   1: 43.180 ±(99.9%) 1.292 ms/op
Iteration   1: 29.037 ±(99.9%) 0.744 ms/op
                 listUser·p0.00:   5.857 ms/op
                 listUser·p0.50:   26.444 ms/op
                 listUser·p0.90:   41.458 ms/op
                 listUser·p0.95:   44.053 ms/op
                 listUser·p0.99:   54.990 ms/op
                 listUser·p0.999:  70.135 ms/op
                 listUser·p0.9999: 71.041 ms/op
                 listUser·p1.00:   71.041 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1097
  mean =     29.037 ±(99.9%) 0.744 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 18 
    [20.000, 25.000) = 309 
    [25.000, 30.000) = 460 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 76 
    [40.000, 45.000) = 89 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 11 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.857 ms/op
     p(50.0000) =     26.444 ms/op
     p(90.0000) =     41.458 ms/op
     p(95.0000) =     44.053 ms/op
     p(99.0000) =     54.990 ms/op
     p(99.9000) =     70.135 ms/op
     p(99.9900) =     71.041 ms/op
     p(99.9990) =     71.041 ms/op
     p(99.9999) =     71.041 ms/op
    p(100.0000) =     71.041 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.128          ops/ms
Client.existUser                       thrpt         2.956          ops/ms
Client.getUser                         thrpt         2.009          ops/ms
Client.listUser                        thrpt         0.811          ops/ms
Client.createUser                       avgt        13.945           ms/op
Client.existUser                        avgt        10.000           ms/op
Client.getUser                          avgt        10.902           ms/op
Client.listUser                         avgt        27.027           ms/op
Client.createUser                     sample  2768  11.918 ± 0.352   ms/op
Client.createUser:createUser·p0.00    sample         7.234           ms/op
Client.createUser:createUser·p0.50    sample         9.945           ms/op
Client.createUser:createUser·p0.90    sample        16.730           ms/op
Client.createUser:createUser·p0.95    sample        23.283           ms/op
Client.createUser:createUser·p0.99    sample        40.829           ms/op
Client.createUser:createUser·p0.999   sample        42.336           ms/op
Client.createUser:createUser·p0.9999  sample        42.467           ms/op
Client.createUser:createUser·p1.00    sample        42.467           ms/op
Client.existUser                      sample  4395   7.294 ± 0.149   ms/op
Client.existUser:existUser·p0.00      sample         1.083           ms/op
Client.existUser:existUser·p0.50      sample         7.037           ms/op
Client.existUser:existUser·p0.90      sample         9.437           ms/op
Client.existUser:existUser·p0.95      sample        11.583           ms/op
Client.existUser:existUser·p0.99      sample        22.318           ms/op
Client.existUser:existUser·p0.999     sample        25.461           ms/op
Client.existUser:existUser·p0.9999    sample        27.886           ms/op
Client.existUser:existUser·p1.00      sample        27.886           ms/op
Client.getUser                        sample  3837   8.285 ± 0.189   ms/op
Client.getUser:getUser·p0.00          sample         2.363           ms/op
Client.getUser:getUser·p0.50          sample         7.627           ms/op
Client.getUser:getUser·p0.90          sample        10.817           ms/op
Client.getUser:getUser·p0.95          sample        14.772           ms/op
Client.getUser:getUser·p0.99          sample        21.713           ms/op
Client.getUser:getUser·p0.999         sample        39.332           ms/op
Client.getUser:getUser·p0.9999        sample        40.305           ms/op
Client.getUser:getUser·p1.00          sample        40.305           ms/op
Client.listUser                       sample  1097  29.037 ± 0.744   ms/op
Client.listUser:listUser·p0.00        sample         5.857           ms/op
Client.listUser:listUser·p0.50        sample        26.444           ms/op
Client.listUser:listUser·p0.90        sample        41.458           ms/op
Client.listUser:listUser·p0.95        sample        44.053           ms/op
Client.listUser:listUser·p0.99        sample        54.990           ms/op
Client.listUser:listUser·p0.999       sample        70.135           ms/op
Client.listUser:listUser·p0.9999      sample        71.041           ms/op
Client.listUser:listUser·p1.00        sample        71.041           ms/op
