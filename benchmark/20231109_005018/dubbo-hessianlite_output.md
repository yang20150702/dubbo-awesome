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
# Warmup Iteration   1: 2.005 ops/ms
Iteration   1: 6.327 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.327 ops/ms


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
# Warmup Iteration   1: 5.981 ops/ms
Iteration   1: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.047 ops/ms


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
# Warmup Iteration   1: 4.680 ops/ms
Iteration   1: 10.142 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.142 ops/ms


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
# Warmup Iteration   1: 2.528 ops/ms
Iteration   1: 3.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.315 ops/ms


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.080 ms/op
Iteration   1: 3.159 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.159 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.039 ms/op
Iteration   1: 1.872 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.872 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.051 ms/op
Iteration   1: 2.948 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.948 ms/op


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
# Warmup Iteration   1: 11.554 ±(99.9%) 0.259 ms/op
Iteration   1: 8.140 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.140 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.102 ms/op
Iteration   1: 2.929 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.693 ms/op
                 createUser·p0.99:   8.272 ms/op
                 createUser·p0.999:  23.920 ms/op
                 createUser·p0.9999: 24.792 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11005
  mean =      2.929 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3461 
    [ 2.500,  5.000) = 7172 
    [ 5.000,  7.500) = 237 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.693 ms/op
     p(99.0000) =      8.272 ms/op
     p(99.9000) =     23.920 ms/op
     p(99.9900) =     24.792 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 2.990 ±(99.9%) 0.060 ms/op
Iteration   1: 1.723 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.249 ms/op
                 existUser·p0.99:   3.096 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 14.207 ms/op
                 existUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18552
  mean =      1.723 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 17568 
    [ 2.500,  3.750) = 260 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.249 ms/op
     p(99.0000) =      3.096 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     14.207 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.100 ms/op
Iteration   1: 3.245 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  16.032 ms/op
                 getUser·p0.9999: 16.432 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10100
  mean =      3.245 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1409 
    [ 2.500,  3.750) = 6946 
    [ 3.750,  5.000) = 1502 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     16.032 ms/op
     p(99.9900) =     16.432 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 11.782 ±(99.9%) 0.382 ms/op
Iteration   1: 7.810 ±(99.9%) 0.110 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   7.512 ms/op
                 listUser·p0.90:   9.876 ms/op
                 listUser·p0.95:   11.185 ms/op
                 listUser·p0.99:   16.932 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4081
  mean =      7.810 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 126 
    [ 5.000,  7.500) = 1902 
    [ 7.500, 10.000) = 1671 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      7.512 ms/op
     p(90.0000) =      9.876 ms/op
     p(95.0000) =     11.185 ms/op
     p(99.0000) =     16.932 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.327          ops/ms
Client.existUser                       thrpt         13.047          ops/ms
Client.getUser                         thrpt         10.142          ops/ms
Client.listUser                        thrpt          3.315          ops/ms
Client.createUser                       avgt          3.159           ms/op
Client.existUser                        avgt          1.872           ms/op
Client.getUser                          avgt          2.948           ms/op
Client.listUser                         avgt          8.140           ms/op
Client.createUser                     sample  11005   2.929 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          1.143           ms/op
Client.createUser:createUser·p0.50    sample          2.687           ms/op
Client.createUser:createUser·p0.90    sample          3.387           ms/op
Client.createUser:createUser·p0.95    sample          3.693           ms/op
Client.createUser:createUser·p0.99    sample          8.272           ms/op
Client.createUser:createUser·p0.999   sample         23.920           ms/op
Client.createUser:createUser·p0.9999  sample         24.792           ms/op
Client.createUser:createUser·p1.00    sample         24.805           ms/op
Client.existUser                      sample  18552   1.723 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.625           ms/op
Client.existUser:existUser·p0.50      sample          1.606           ms/op
Client.existUser:existUser·p0.90      sample          2.101           ms/op
Client.existUser:existUser·p0.95      sample          2.249           ms/op
Client.existUser:existUser·p0.99      sample          3.096           ms/op
Client.existUser:existUser·p0.999     sample         14.090           ms/op
Client.existUser:existUser·p0.9999    sample         14.207           ms/op
Client.existUser:existUser·p1.00      sample         14.221           ms/op
Client.getUser                        sample  10100   3.245 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          1.167           ms/op
Client.getUser:getUser·p0.50          sample          3.146           ms/op
Client.getUser:getUser·p0.90          sample          3.969           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          6.709           ms/op
Client.getUser:getUser·p0.999         sample         16.032           ms/op
Client.getUser:getUser·p0.9999        sample         16.432           ms/op
Client.getUser:getUser·p1.00          sample         16.433           ms/op
Client.listUser                       sample   4081   7.810 ± 0.110   ms/op
Client.listUser:listUser·p0.00        sample          2.044           ms/op
Client.listUser:listUser·p0.50        sample          7.512           ms/op
Client.listUser:listUser·p0.90        sample          9.876           ms/op
Client.listUser:listUser·p0.95        sample         11.185           ms/op
Client.listUser:listUser·p0.99        sample         16.932           ms/op
Client.listUser:listUser·p0.999       sample         21.496           ms/op
Client.listUser:listUser·p0.9999      sample         24.936           ms/op
Client.listUser:listUser·p1.00        sample         24.936           ms/op
