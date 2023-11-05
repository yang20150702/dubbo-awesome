# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
Iteration   1: 6.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.380 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.812 ops/ms
Iteration   1: 14.477 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.477 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ops/ms
Iteration   1: 8.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.905 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
Iteration   1: 3.509 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.509 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.054 ms/op
Iteration   1: 3.249 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.249 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.043 ±(99.9%) 0.033 ms/op
Iteration   1: 1.897 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ±(99.9%) 0.046 ms/op
Iteration   1: 2.902 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.902 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.090 ±(99.9%) 0.235 ms/op
Iteration   1: 7.198 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.198 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.652 ±(99.9%) 0.094 ms/op
Iteration   1: 2.731 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.458 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.938 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  13.897 ms/op
                 createUser·p0.9999: 14.663 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11691
  mean =      2.731 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 6436 
    [ 2.500,  3.750) = 4261 
    [ 3.750,  5.000) = 806 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.938 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.897 ms/op
     p(99.9900) =     14.663 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.755 ±(99.9%) 0.049 ms/op
Iteration   1: 1.463 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.452 ms/op
                 existUser·p0.50:   1.372 ms/op
                 existUser·p0.90:   1.815 ms/op
                 existUser·p0.95:   1.980 ms/op
                 existUser·p0.99:   2.494 ms/op
                 existUser·p0.999:  19.595 ms/op
                 existUser·p0.9999: 20.232 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 21844
  mean =      1.463 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21630 
    [ 2.500,  5.000) = 170 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      1.372 ms/op
     p(90.0000) =      1.815 ms/op
     p(95.0000) =      1.980 ms/op
     p(99.0000) =      2.494 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     20.232 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.170 ms/op
Iteration   1: 2.808 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.716 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.756 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 12.203 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11439
  mean =      2.808 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 3262 
    [ 2.500,  3.750) = 7609 
    [ 3.750,  5.000) = 443 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.756 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     12.203 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.199 ±(99.9%) 0.368 ms/op
Iteration   1: 8.202 ±(99.9%) 0.143 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   7.643 ms/op
                 listUser·p0.90:   11.256 ms/op
                 listUser·p0.95:   12.452 ms/op
                 listUser·p0.99:   18.458 ms/op
                 listUser·p0.999:  25.952 ms/op
                 listUser·p0.9999: 26.575 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3896
  mean =      8.202 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 159 
    [ 5.000,  7.500) = 1649 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.507 ms/op
     p(50.0000) =      7.643 ms/op
     p(90.0000) =     11.256 ms/op
     p(95.0000) =     12.452 ms/op
     p(99.0000) =     18.458 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.380          ops/ms
Client.existUser                       thrpt         14.477          ops/ms
Client.getUser                         thrpt          8.905          ops/ms
Client.listUser                        thrpt          3.509          ops/ms
Client.createUser                       avgt          3.249           ms/op
Client.existUser                        avgt          1.897           ms/op
Client.getUser                          avgt          2.902           ms/op
Client.listUser                         avgt          7.198           ms/op
Client.createUser                     sample  11691   2.731 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.002           ms/op
Client.createUser:createUser·p0.50    sample          2.458           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          3.938           ms/op
Client.createUser:createUser·p0.99    sample          5.505           ms/op
Client.createUser:createUser·p0.999   sample         13.897           ms/op
Client.createUser:createUser·p0.9999  sample         14.663           ms/op
Client.createUser:createUser·p1.00    sample         14.680           ms/op
Client.existUser                      sample  21844   1.463 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.452           ms/op
Client.existUser:existUser·p0.50      sample          1.372           ms/op
Client.existUser:existUser·p0.90      sample          1.815           ms/op
Client.existUser:existUser·p0.95      sample          1.980           ms/op
Client.existUser:existUser·p0.99      sample          2.494           ms/op
Client.existUser:existUser·p0.999     sample         19.595           ms/op
Client.existUser:existUser·p0.9999    sample         20.232           ms/op
Client.existUser:existUser·p1.00      sample         20.349           ms/op
Client.getUser                        sample  11439   2.808 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.670           ms/op
Client.getUser:getUser·p0.50          sample          2.716           ms/op
Client.getUser:getUser·p0.90          sample          3.449           ms/op
Client.getUser:getUser·p0.95          sample          3.731           ms/op
Client.getUser:getUser·p0.99          sample          4.756           ms/op
Client.getUser:getUser·p0.999         sample         10.469           ms/op
Client.getUser:getUser·p0.9999        sample         12.203           ms/op
Client.getUser:getUser·p1.00          sample         12.288           ms/op
Client.listUser                       sample   3896   8.202 ± 0.143   ms/op
Client.listUser:listUser·p0.00        sample          2.507           ms/op
Client.listUser:listUser·p0.50        sample          7.643           ms/op
Client.listUser:listUser·p0.90        sample         11.256           ms/op
Client.listUser:listUser·p0.95        sample         12.452           ms/op
Client.listUser:listUser·p0.99        sample         18.458           ms/op
Client.listUser:listUser·p0.999       sample         25.952           ms/op
Client.listUser:listUser·p0.9999      sample         26.575           ms/op
Client.listUser:listUser·p1.00        sample         26.575           ms/op
