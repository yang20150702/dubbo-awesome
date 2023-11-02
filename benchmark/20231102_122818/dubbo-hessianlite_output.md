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
# Warmup Iteration   1: 1.635 ops/ms
Iteration   1: 4.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.121 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ops/ms
Iteration   1: 11.479 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.479 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
Iteration   1: 5.569 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.569 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.077 ops/ms
Iteration   1: 1.284 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.284 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 13.661 ±(99.9%) 0.276 ms/op
Iteration   1: 5.765 ±(99.9%) 0.137 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.765 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 5.075 ±(99.9%) 0.068 ms/op
Iteration   1: 2.088 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.088 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.879 ±(99.9%) 0.278 ms/op
Iteration   1: 4.185 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.185 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 24.439 ±(99.9%) 0.509 ms/op
Iteration   1: 17.001 ±(99.9%) 0.272 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.001 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.748 ±(99.9%) 0.329 ms/op
Iteration   1: 4.589 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   9.683 ms/op
                 createUser·p0.99:   16.637 ms/op
                 createUser·p0.999:  20.548 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6955
  mean =      4.589 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 5117 
    [ 5.000,  7.500) = 1254 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     16.637 ms/op
     p(99.9000) =     20.548 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.843 ±(99.9%) 0.247 ms/op
Iteration   1: 2.445 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.458 ms/op
                 existUser·p0.50:   1.997 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   5.435 ms/op
                 existUser·p0.99:   11.583 ms/op
                 existUser·p0.999:  21.660 ms/op
                 existUser·p0.9999: 22.097 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13224
  mean =      2.445 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11168 
    [ 2.500,  5.000) = 1329 
    [ 5.000,  7.500) = 375 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      5.435 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     22.097 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ±(99.9%) 0.261 ms/op
Iteration   1: 3.476 ±(99.9%) 0.067 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   11.010 ms/op
                 getUser·p0.999:  28.836 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9196
  mean =      3.476 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 712 
    [ 2.500,  5.000) = 7734 
    [ 5.000,  7.500) = 471 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     28.836 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 23.543 ±(99.9%) 0.920 ms/op
Iteration   1: 14.700 ±(99.9%) 0.378 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   13.844 ms/op
                 listUser·p0.90:   20.113 ms/op
                 listUser·p0.95:   22.656 ms/op
                 listUser·p0.99:   31.868 ms/op
                 listUser·p0.999:  52.067 ms/op
                 listUser·p0.9999: 52.625 ms/op
                 listUser·p1.00:   52.625 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2171
  mean =     14.700 ±(99.9%) 0.378 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 35 
    [ 5.000, 10.000) = 173 
    [10.000, 15.000) = 1130 
    [15.000, 20.000) = 612 
    [20.000, 25.000) = 157 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =     13.844 ms/op
     p(90.0000) =     20.113 ms/op
     p(95.0000) =     22.656 ms/op
     p(99.0000) =     31.868 ms/op
     p(99.9000) =     52.067 ms/op
     p(99.9900) =     52.625 ms/op
     p(99.9990) =     52.625 ms/op
     p(99.9999) =     52.625 ms/op
    p(100.0000) =     52.625 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.121          ops/ms
Client.existUser                       thrpt         11.479          ops/ms
Client.getUser                         thrpt          5.569          ops/ms
Client.listUser                        thrpt          1.284          ops/ms
Client.createUser                       avgt          5.765           ms/op
Client.existUser                        avgt          2.088           ms/op
Client.getUser                          avgt          4.185           ms/op
Client.listUser                         avgt         17.001           ms/op
Client.createUser                     sample   6955   4.589 ± 0.106   ms/op
Client.createUser:createUser·p0.00    sample          1.694           ms/op
Client.createUser:createUser·p0.50    sample          3.817           ms/op
Client.createUser:createUser·p0.90    sample          7.160           ms/op
Client.createUser:createUser·p0.95    sample          9.683           ms/op
Client.createUser:createUser·p0.99    sample         16.637           ms/op
Client.createUser:createUser·p0.999   sample         20.548           ms/op
Client.createUser:createUser·p0.9999  sample         21.725           ms/op
Client.createUser:createUser·p1.00    sample         21.725           ms/op
Client.existUser                      sample  13224   2.445 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample          0.458           ms/op
Client.existUser:existUser·p0.50      sample          1.997           ms/op
Client.existUser:existUser·p0.90      sample          3.006           ms/op
Client.existUser:existUser·p0.95      sample          5.435           ms/op
Client.existUser:existUser·p0.99      sample         11.583           ms/op
Client.existUser:existUser·p0.999     sample         21.660           ms/op
Client.existUser:existUser·p0.9999    sample         22.097           ms/op
Client.existUser:existUser·p1.00      sample         22.118           ms/op
Client.getUser                        sample   9196   3.476 ± 0.067   ms/op
Client.getUser:getUser·p0.00          sample          0.956           ms/op
Client.getUser:getUser·p0.50          sample          3.129           ms/op
Client.getUser:getUser·p0.90          sample          4.284           ms/op
Client.getUser:getUser·p0.95          sample          5.890           ms/op
Client.getUser:getUser·p0.99          sample         11.010           ms/op
Client.getUser:getUser·p0.999         sample         28.836           ms/op
Client.getUser:getUser·p0.9999        sample         31.818           ms/op
Client.getUser:getUser·p1.00          sample         31.818           ms/op
Client.listUser                       sample   2171  14.700 ± 0.378   ms/op
Client.listUser:listUser·p0.00        sample          1.489           ms/op
Client.listUser:listUser·p0.50        sample         13.844           ms/op
Client.listUser:listUser·p0.90        sample         20.113           ms/op
Client.listUser:listUser·p0.95        sample         22.656           ms/op
Client.listUser:listUser·p0.99        sample         31.868           ms/op
Client.listUser:listUser·p0.999       sample         52.067           ms/op
Client.listUser:listUser·p0.9999      sample         52.625           ms/op
Client.listUser:listUser·p1.00        sample         52.625           ms/op
