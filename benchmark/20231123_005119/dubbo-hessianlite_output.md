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
# Warmup Iteration   1: 2.444 ops/ms
Iteration   1: 5.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.352 ops/ms


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
# Warmup Iteration   1: 6.009 ops/ms
Iteration   1: 13.642 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.642 ops/ms


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
# Warmup Iteration   1: 3.895 ops/ms
Iteration   1: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.350 ops/ms


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
# Warmup Iteration   1: 2.360 ops/ms
Iteration   1: 4.261 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.261 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ±(99.9%) 0.064 ms/op
Iteration   1: 3.444 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.444 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ±(99.9%) 0.042 ms/op
Iteration   1: 1.941 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.941 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.055 ms/op
Iteration   1: 2.710 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.710 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.683 ±(99.9%) 0.221 ms/op
Iteration   1: 8.855 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.855 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ±(99.9%) 0.090 ms/op
Iteration   1: 2.804 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.396 ms/op
                 createUser·p0.999:  15.833 ms/op
                 createUser·p0.9999: 16.773 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11403
  mean =      2.804 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 4445 
    [ 2.500,  3.750) = 6139 
    [ 3.750,  5.000) = 619 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.396 ms/op
     p(99.9000) =     15.833 ms/op
     p(99.9900) =     16.773 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ±(99.9%) 0.086 ms/op
Iteration   1: 2.082 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   1.882 ms/op
                 existUser·p0.90:   2.609 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  26.998 ms/op
                 existUser·p0.9999: 27.473 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15296
  mean =      2.082 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13307 
    [ 2.500,  5.000) = 1816 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     26.998 ms/op
     p(99.9900) =     27.473 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.083 ms/op
Iteration   1: 2.906 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.744 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.927 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 13.248 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11002
  mean =      2.906 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 3291 
    [ 2.500,  3.750) = 6939 
    [ 3.750,  5.000) = 615 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.744 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.927 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     13.248 ms/op
     p(99.9990) =     13.271 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


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
# Warmup Iteration   1: 15.268 ±(99.9%) 0.479 ms/op
Iteration   1: 10.885 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   10.502 ms/op
                 listUser·p0.90:   14.288 ms/op
                 listUser·p0.95:   15.418 ms/op
                 listUser·p0.99:   20.860 ms/op
                 listUser·p0.999:  24.534 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2938
  mean =     10.885 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 17 
    [ 5.000,  7.500) = 187 
    [ 7.500, 10.000) = 1015 
    [10.000, 12.500) = 1014 
    [12.500, 15.000) = 523 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.814 ms/op
     p(50.0000) =     10.502 ms/op
     p(90.0000) =     14.288 ms/op
     p(95.0000) =     15.418 ms/op
     p(99.0000) =     20.860 ms/op
     p(99.9000) =     24.534 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.352          ops/ms
Client.existUser                       thrpt         13.642          ops/ms
Client.getUser                         thrpt          8.350          ops/ms
Client.listUser                        thrpt          4.261          ops/ms
Client.createUser                       avgt          3.444           ms/op
Client.existUser                        avgt          1.941           ms/op
Client.getUser                          avgt          2.710           ms/op
Client.listUser                         avgt          8.855           ms/op
Client.createUser                     sample  11403   2.804 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.049           ms/op
Client.createUser:createUser·p0.50    sample          2.630           ms/op
Client.createUser:createUser·p0.90    sample          3.445           ms/op
Client.createUser:createUser·p0.95    sample          4.137           ms/op
Client.createUser:createUser·p0.99    sample          6.396           ms/op
Client.createUser:createUser·p0.999   sample         15.833           ms/op
Client.createUser:createUser·p0.9999  sample         16.773           ms/op
Client.createUser:createUser·p1.00    sample         16.777           ms/op
Client.existUser                      sample  15296   2.082 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample          0.759           ms/op
Client.existUser:existUser·p0.50      sample          1.882           ms/op
Client.existUser:existUser·p0.90      sample          2.609           ms/op
Client.existUser:existUser·p0.95      sample          3.002           ms/op
Client.existUser:existUser·p0.99      sample          5.128           ms/op
Client.existUser:existUser·p0.999     sample         26.998           ms/op
Client.existUser:existUser·p0.9999    sample         27.473           ms/op
Client.existUser:existUser·p1.00      sample         27.525           ms/op
Client.getUser                        sample  11002   2.906 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.896           ms/op
Client.getUser:getUser·p0.50          sample          2.744           ms/op
Client.getUser:getUser·p0.90          sample          3.641           ms/op
Client.getUser:getUser·p0.95          sample          3.927           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample         12.272           ms/op
Client.getUser:getUser·p0.9999        sample         13.248           ms/op
Client.getUser:getUser·p1.00          sample         13.271           ms/op
Client.listUser                       sample   2938  10.885 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample          2.814           ms/op
Client.listUser:listUser·p0.50        sample         10.502           ms/op
Client.listUser:listUser·p0.90        sample         14.288           ms/op
Client.listUser:listUser·p0.95        sample         15.418           ms/op
Client.listUser:listUser·p0.99        sample         20.860           ms/op
Client.listUser:listUser·p0.999       sample         24.534           ms/op
Client.listUser:listUser·p0.9999      sample         25.854           ms/op
Client.listUser:listUser·p1.00        sample         25.854           ms/op
