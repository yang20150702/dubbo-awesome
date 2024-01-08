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
# Warmup Iteration   1: 2.436 ops/ms
Iteration   1: 6.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.401 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.406 ops/ms
Iteration   1: 12.921 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.921 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ops/ms
Iteration   1: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.941 ops/ms


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
# Warmup Iteration   1: 2.240 ops/ms
Iteration   1: 4.155 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.155 ops/ms


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
# Warmup Iteration   1: 5.726 ±(99.9%) 0.124 ms/op
Iteration   1: 3.009 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.009 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.027 ms/op
Iteration   1: 2.047 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.047 ms/op


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.057 ms/op
Iteration   1: 3.025 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.025 ms/op


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
# Warmup Iteration   1: 11.721 ±(99.9%) 0.326 ms/op
Iteration   1: 8.823 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.823 ms/op


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.108 ms/op
Iteration   1: 3.048 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.006 ms/op
                 createUser·p0.999:  13.746 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10479
  mean =      3.048 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2126 
    [ 2.500,  3.750) = 7472 
    [ 3.750,  5.000) = 609 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.006 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.002 ±(99.9%) 0.070 ms/op
Iteration   1: 1.696 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   1.569 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  14.008 ms/op
                 existUser·p0.9999: 14.917 ms/op
                 existUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18858
  mean =      1.696 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1387 
    [ 1.250,  2.500) = 16855 
    [ 2.500,  3.750) = 462 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      1.569 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     14.917 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.112 ms/op
Iteration   1: 2.993 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.620 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  5.612 ms/op
                 getUser·p0.9999: 6.389 ms/op
                 getUser·p1.00:   6.423 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10780
  mean =      2.993 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 96 
    [2.000, 2.500) = 1705 
    [2.500, 3.000) = 3930 
    [3.000, 3.500) = 3475 
    [3.500, 4.000) = 1226 
    [4.000, 4.500) = 145 
    [4.500, 5.000) = 118 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.620 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      5.612 ms/op
     p(99.9900) =      6.389 ms/op
     p(99.9990) =      6.423 ms/op
     p(99.9999) =      6.423 ms/op
    p(100.0000) =      6.423 ms/op


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
# Warmup Iteration   1: 11.283 ±(99.9%) 0.380 ms/op
Iteration   1: 7.226 ±(99.9%) 0.081 ms/op
                 listUser·p0.00:   3.269 ms/op
                 listUser·p0.50:   7.062 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   12.615 ms/op
                 listUser·p0.999:  18.327 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4566
  mean =      7.226 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 187 
    [ 5.000,  7.500) = 2742 
    [ 7.500, 10.000) = 1455 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.269 ms/op
     p(50.0000) =      7.062 ms/op
     p(90.0000) =      8.962 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     12.615 ms/op
     p(99.9000) =     18.327 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.401          ops/ms
Client.existUser                       thrpt         12.921          ops/ms
Client.getUser                         thrpt          7.941          ops/ms
Client.listUser                        thrpt          4.155          ops/ms
Client.createUser                       avgt          3.009           ms/op
Client.existUser                        avgt          2.047           ms/op
Client.getUser                          avgt          3.025           ms/op
Client.listUser                         avgt          8.823           ms/op
Client.createUser                     sample  10479   3.048 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.110           ms/op
Client.createUser:createUser·p0.50    sample          2.949           ms/op
Client.createUser:createUser·p0.90    sample          3.633           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample          6.006           ms/op
Client.createUser:createUser·p0.999   sample         13.746           ms/op
Client.createUser:createUser·p0.9999  sample         13.959           ms/op
Client.createUser:createUser·p1.00    sample         13.959           ms/op
Client.existUser                      sample  18858   1.696 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.766           ms/op
Client.existUser:existUser·p0.50      sample          1.569           ms/op
Client.existUser:existUser·p0.90      sample          2.204           ms/op
Client.existUser:existUser·p0.95      sample          2.367           ms/op
Client.existUser:existUser·p0.99      sample          3.637           ms/op
Client.existUser:existUser·p0.999     sample         14.008           ms/op
Client.existUser:existUser·p0.9999    sample         14.917           ms/op
Client.existUser:existUser·p1.00      sample         14.975           ms/op
Client.getUser                        sample  10780   2.993 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          1.090           ms/op
Client.getUser:getUser·p0.50          sample          2.941           ms/op
Client.getUser:getUser·p0.90          sample          3.620           ms/op
Client.getUser:getUser·p0.95          sample          3.842           ms/op
Client.getUser:getUser·p0.99          sample          4.751           ms/op
Client.getUser:getUser·p0.999         sample          5.612           ms/op
Client.getUser:getUser·p0.9999        sample          6.389           ms/op
Client.getUser:getUser·p1.00          sample          6.423           ms/op
Client.listUser                       sample   4566   7.226 ± 0.081   ms/op
Client.listUser:listUser·p0.00        sample          3.269           ms/op
Client.listUser:listUser·p0.50        sample          7.062           ms/op
Client.listUser:listUser·p0.90        sample          8.962           ms/op
Client.listUser:listUser·p0.95        sample          9.765           ms/op
Client.listUser:listUser·p0.99        sample         12.615           ms/op
Client.listUser:listUser·p0.999       sample         18.327           ms/op
Client.listUser:listUser·p0.9999      sample         20.873           ms/op
Client.listUser:listUser·p1.00        sample         20.873           ms/op
