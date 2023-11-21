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
# Warmup Iteration   1: 2.265 ops/ms
Iteration   1: 5.691 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.691 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.503 ops/ms
Iteration   1: 13.939 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.939 ops/ms


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
# Warmup Iteration   1: 4.805 ops/ms
Iteration   1: 8.547 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.547 ops/ms


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
# Warmup Iteration   1: 2.331 ops/ms
Iteration   1: 4.149 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.149 ops/ms


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
# Warmup Iteration   1: 5.349 ±(99.9%) 0.071 ms/op
Iteration   1: 3.183 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.183 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.035 ms/op
Iteration   1: 2.016 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.016 ms/op


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
# Warmup Iteration   1: 4.515 ±(99.9%) 0.064 ms/op
Iteration   1: 2.710 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 12.673 ±(99.9%) 0.283 ms/op
Iteration   1: 8.999 ±(99.9%) 0.163 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.999 ms/op


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
# Warmup Iteration   1: 5.690 ±(99.9%) 0.212 ms/op
Iteration   1: 3.538 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   13.192 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9039
  mean =      3.538 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 524 
    [ 2.500,  5.000) = 8071 
    [ 5.000,  7.500) = 273 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =     13.192 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.071 ms/op
Iteration   1: 1.908 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   1.843 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 14.027 ms/op
                 existUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16784
  mean =      1.908 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 518 
    [ 1.250,  2.500) = 15211 
    [ 2.500,  3.750) = 924 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     14.027 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.093 ms/op
Iteration   1: 3.343 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.071 ms/op
                 getUser·p0.999:  16.381 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9577
  mean =      3.343 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1368 
    [ 2.500,  3.750) = 6204 
    [ 3.750,  5.000) = 1513 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.071 ms/op
     p(99.9000) =     16.381 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 11.518 ±(99.9%) 0.440 ms/op
Iteration   1: 7.909 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   7.643 ms/op
                 listUser·p0.90:   10.240 ms/op
                 listUser·p0.95:   11.665 ms/op
                 listUser·p0.99:   15.217 ms/op
                 listUser·p0.999:  23.345 ms/op
                 listUser·p0.9999: 30.704 ms/op
                 listUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4044
  mean =      7.909 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 145 
    [ 5.000,  7.500) = 1732 
    [ 7.500, 10.000) = 1688 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      7.643 ms/op
     p(90.0000) =     10.240 ms/op
     p(95.0000) =     11.665 ms/op
     p(99.0000) =     15.217 ms/op
     p(99.9000) =     23.345 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.691          ops/ms
Client.existUser                       thrpt         13.939          ops/ms
Client.getUser                         thrpt          8.547          ops/ms
Client.listUser                        thrpt          4.149          ops/ms
Client.createUser                       avgt          3.183           ms/op
Client.existUser                        avgt          2.016           ms/op
Client.getUser                          avgt          2.710           ms/op
Client.listUser                         avgt          8.999           ms/op
Client.createUser                     sample   9039   3.538 ± 0.053   ms/op
Client.createUser:createUser·p0.00    sample          1.241           ms/op
Client.createUser:createUser·p0.50    sample          3.297           ms/op
Client.createUser:createUser·p0.90    sample          4.137           ms/op
Client.createUser:createUser·p0.95    sample          4.956           ms/op
Client.createUser:createUser·p0.99    sample         13.192           ms/op
Client.createUser:createUser·p0.999   sample         19.825           ms/op
Client.createUser:createUser·p0.9999  sample         21.561           ms/op
Client.createUser:createUser·p1.00    sample         21.561           ms/op
Client.existUser                      sample  16784   1.908 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.677           ms/op
Client.existUser:existUser·p0.50      sample          1.843           ms/op
Client.existUser:existUser·p0.90      sample          2.355           ms/op
Client.existUser:existUser·p0.95      sample          2.576           ms/op
Client.existUser:existUser·p0.99      sample          3.662           ms/op
Client.existUser:existUser·p0.999     sample         13.304           ms/op
Client.existUser:existUser·p0.9999    sample         14.027           ms/op
Client.existUser:existUser·p1.00      sample         14.516           ms/op
Client.getUser                        sample   9577   3.343 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.910           ms/op
Client.getUser:getUser·p0.50          sample          3.174           ms/op
Client.getUser:getUser·p0.90          sample          4.284           ms/op
Client.getUser:getUser·p0.95          sample          4.997           ms/op
Client.getUser:getUser·p0.99          sample          7.071           ms/op
Client.getUser:getUser·p0.999         sample         16.381           ms/op
Client.getUser:getUser·p0.9999        sample         17.269           ms/op
Client.getUser:getUser·p1.00          sample         17.269           ms/op
Client.listUser                       sample   4044   7.909 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          2.142           ms/op
Client.listUser:listUser·p0.50        sample          7.643           ms/op
Client.listUser:listUser·p0.90        sample         10.240           ms/op
Client.listUser:listUser·p0.95        sample         11.665           ms/op
Client.listUser:listUser·p0.99        sample         15.217           ms/op
Client.listUser:listUser·p0.999       sample         23.345           ms/op
Client.listUser:listUser·p0.9999      sample         30.704           ms/op
Client.listUser:listUser·p1.00        sample         30.704           ms/op
