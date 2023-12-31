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
# Warmup Iteration   1: 2.285 ops/ms
Iteration   1: 5.534 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.534 ops/ms


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
# Warmup Iteration   1: 5.490 ops/ms
Iteration   1: 12.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.410 ops/ms


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
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 8.132 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.132 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
Iteration   1: 3.517 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.517 ops/ms


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
# Warmup Iteration   1: 5.774 ±(99.9%) 0.066 ms/op
Iteration   1: 3.337 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.337 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.041 ms/op
Iteration   1: 1.934 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.934 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.049 ms/op
Iteration   1: 3.428 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.428 ms/op


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
# Warmup Iteration   1: 13.989 ±(99.9%) 0.396 ms/op
Iteration   1: 8.641 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.641 ms/op


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
# Warmup Iteration   1: 5.154 ±(99.9%) 0.122 ms/op
Iteration   1: 2.817 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.234 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  14.478 ms/op
                 createUser·p0.9999: 15.963 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11343
  mean =      2.817 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2775 
    [ 2.500,  3.750) = 8201 
    [ 3.750,  5.000) = 202 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.234 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.478 ms/op
     p(99.9900) =     15.963 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.101 ms/op
Iteration   1: 2.102 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.954 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  10.167 ms/op
                 existUser·p0.9999: 11.402 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15438
  mean =      2.102 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 13129 
    [ 2.500,  3.750) = 1714 
    [ 3.750,  5.000) = 264 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     10.167 ms/op
     p(99.9900) =     11.402 ms/op
     p(99.9990) =     11.420 ms/op
     p(99.9999) =     11.420 ms/op
    p(100.0000) =     11.420 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ±(99.9%) 0.109 ms/op
Iteration   1: 3.063 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.631 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 9.110 ms/op
                 getUser·p1.00:   9.110 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10461
  mean =      3.063 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 344 
    [ 2.000,  3.000) = 5051 
    [ 3.000,  4.000) = 4236 
    [ 4.000,  5.000) = 583 
    [ 5.000,  6.000) = 179 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.631 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =      9.110 ms/op
     p(99.9990) =      9.110 ms/op
     p(99.9999) =      9.110 ms/op
    p(100.0000) =      9.110 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.307 ±(99.9%) 0.562 ms/op
Iteration   1: 8.987 ±(99.9%) 0.154 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   8.536 ms/op
                 listUser·p0.90:   12.485 ms/op
                 listUser·p0.95:   14.352 ms/op
                 listUser·p0.99:   17.509 ms/op
                 listUser·p0.999:  25.158 ms/op
                 listUser·p0.9999: 30.179 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3555
  mean =      8.987 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 137 
    [ 5.000,  7.500) = 892 
    [ 7.500, 10.000) = 1518 
    [10.000, 12.500) = 650 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      8.536 ms/op
     p(90.0000) =     12.485 ms/op
     p(95.0000) =     14.352 ms/op
     p(99.0000) =     17.509 ms/op
     p(99.9000) =     25.158 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.534          ops/ms
Client.existUser                       thrpt         12.410          ops/ms
Client.getUser                         thrpt          8.132          ops/ms
Client.listUser                        thrpt          3.517          ops/ms
Client.createUser                       avgt          3.337           ms/op
Client.existUser                        avgt          1.934           ms/op
Client.getUser                          avgt          3.428           ms/op
Client.listUser                         avgt          8.641           ms/op
Client.createUser                     sample  11343   2.817 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.077           ms/op
Client.createUser:createUser·p0.50    sample          2.695           ms/op
Client.createUser:createUser·p0.90    sample          3.234           ms/op
Client.createUser:createUser·p0.95    sample          3.465           ms/op
Client.createUser:createUser·p0.99    sample          6.791           ms/op
Client.createUser:createUser·p0.999   sample         14.478           ms/op
Client.createUser:createUser·p0.9999  sample         15.963           ms/op
Client.createUser:createUser·p1.00    sample         15.974           ms/op
Client.existUser                      sample  15438   2.102 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.567           ms/op
Client.existUser:existUser·p0.50      sample          1.954           ms/op
Client.existUser:existUser·p0.90      sample          2.601           ms/op
Client.existUser:existUser·p0.95      sample          2.912           ms/op
Client.existUser:existUser·p0.99      sample          4.956           ms/op
Client.existUser:existUser·p0.999     sample         10.167           ms/op
Client.existUser:existUser·p0.9999    sample         11.402           ms/op
Client.existUser:existUser·p1.00      sample         11.420           ms/op
Client.getUser                        sample  10461   3.063 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.757           ms/op
Client.getUser:getUser·p0.50          sample          2.957           ms/op
Client.getUser:getUser·p0.90          sample          3.908           ms/op
Client.getUser:getUser·p0.95          sample          4.260           ms/op
Client.getUser:getUser·p0.99          sample          5.631           ms/op
Client.getUser:getUser·p0.999         sample          8.684           ms/op
Client.getUser:getUser·p0.9999        sample          9.110           ms/op
Client.getUser:getUser·p1.00          sample          9.110           ms/op
Client.listUser                       sample   3555   8.987 ± 0.154   ms/op
Client.listUser:listUser·p0.00        sample          1.622           ms/op
Client.listUser:listUser·p0.50        sample          8.536           ms/op
Client.listUser:listUser·p0.90        sample         12.485           ms/op
Client.listUser:listUser·p0.95        sample         14.352           ms/op
Client.listUser:listUser·p0.99        sample         17.509           ms/op
Client.listUser:listUser·p0.999       sample         25.158           ms/op
Client.listUser:listUser·p0.9999      sample         30.179           ms/op
Client.listUser:listUser·p1.00        sample         30.179           ms/op
