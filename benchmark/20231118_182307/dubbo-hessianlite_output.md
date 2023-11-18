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
# Warmup Iteration   1: 2.672 ops/ms
Iteration   1: 5.578 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.578 ops/ms


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
# Warmup Iteration   1: 5.921 ops/ms
Iteration   1: 11.929 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.929 ops/ms


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
# Warmup Iteration   1: 4.872 ops/ms
Iteration   1: 9.402 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.402 ops/ms


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
# Warmup Iteration   1: 2.323 ops/ms
Iteration   1: 3.742 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.742 ops/ms


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.061 ms/op
Iteration   1: 2.991 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.991 ms/op


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
# Warmup Iteration   1: 2.899 ±(99.9%) 0.031 ms/op
Iteration   1: 1.899 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.899 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.076 ms/op
Iteration   1: 2.921 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.921 ms/op


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
# Warmup Iteration   1: 11.707 ±(99.9%) 0.178 ms/op
Iteration   1: 9.225 ±(99.9%) 0.176 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.225 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.097 ms/op
Iteration   1: 2.874 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   4.109 ms/op
                 createUser·p0.99:   8.409 ms/op
                 createUser·p0.999:  13.659 ms/op
                 createUser·p0.9999: 15.458 ms/op
                 createUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11077
  mean =      2.874 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 3793 
    [ 2.500,  3.750) = 6403 
    [ 3.750,  5.000) = 650 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      4.109 ms/op
     p(99.0000) =      8.409 ms/op
     p(99.9000) =     13.659 ms/op
     p(99.9900) =     15.458 ms/op
     p(99.9990) =     15.466 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.244 ms/op
Iteration   1: 1.945 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   3.443 ms/op
                 existUser·p0.999:  15.787 ms/op
                 existUser·p0.9999: 15.987 ms/op
                 existUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16450
  mean =      1.945 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 15185 
    [ 2.500,  3.750) = 1005 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.443 ms/op
     p(99.9000) =     15.787 ms/op
     p(99.9900) =     15.987 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.107 ms/op
Iteration   1: 2.813 ±(99.9%) 0.066 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.534 ms/op
                 getUser·p0.999:  41.536 ms/op
                 getUser·p0.9999: 44.285 ms/op
                 getUser·p1.00:   44.564 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11641
  mean =      2.813 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11484 
    [ 5.000, 10.000) = 89 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.534 ms/op
     p(99.9000) =     41.536 ms/op
     p(99.9900) =     44.285 ms/op
     p(99.9990) =     44.564 ms/op
     p(99.9999) =     44.564 ms/op
    p(100.0000) =     44.564 ms/op


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
# Warmup Iteration   1: 12.114 ±(99.9%) 0.358 ms/op
Iteration   1: 7.146 ±(99.9%) 0.102 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   6.717 ms/op
                 listUser·p0.90:   9.676 ms/op
                 listUser·p0.95:   11.043 ms/op
                 listUser·p0.99:   14.896 ms/op
                 listUser·p0.999:  19.516 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4483
  mean =      7.146 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 374 
    [ 5.000,  7.500) = 2693 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.675 ms/op
     p(50.0000) =      6.717 ms/op
     p(90.0000) =      9.676 ms/op
     p(95.0000) =     11.043 ms/op
     p(99.0000) =     14.896 ms/op
     p(99.9000) =     19.516 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.578          ops/ms
Client.existUser                       thrpt         11.929          ops/ms
Client.getUser                         thrpt          9.402          ops/ms
Client.listUser                        thrpt          3.742          ops/ms
Client.createUser                       avgt          2.991           ms/op
Client.existUser                        avgt          1.899           ms/op
Client.getUser                          avgt          2.921           ms/op
Client.listUser                         avgt          9.225           ms/op
Client.createUser                     sample  11077   2.874 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.075           ms/op
Client.createUser:createUser·p0.50    sample          2.671           ms/op
Client.createUser:createUser·p0.90    sample          3.510           ms/op
Client.createUser:createUser·p0.95    sample          4.109           ms/op
Client.createUser:createUser·p0.99    sample          8.409           ms/op
Client.createUser:createUser·p0.999   sample         13.659           ms/op
Client.createUser:createUser·p0.9999  sample         15.458           ms/op
Client.createUser:createUser·p1.00    sample         15.466           ms/op
Client.existUser                      sample  16450   1.945 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.671           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.343           ms/op
Client.existUser:existUser·p0.95      sample          2.613           ms/op
Client.existUser:existUser·p0.99      sample          3.443           ms/op
Client.existUser:existUser·p0.999     sample         15.787           ms/op
Client.existUser:existUser·p0.9999    sample         15.987           ms/op
Client.existUser:existUser·p1.00      sample         16.040           ms/op
Client.getUser                        sample  11641   2.813 ± 0.066   ms/op
Client.getUser:getUser·p0.00          sample          0.914           ms/op
Client.getUser:getUser·p0.50          sample          2.576           ms/op
Client.getUser:getUser·p0.90          sample          3.523           ms/op
Client.getUser:getUser·p0.95          sample          3.969           ms/op
Client.getUser:getUser·p0.99          sample          6.534           ms/op
Client.getUser:getUser·p0.999         sample         41.536           ms/op
Client.getUser:getUser·p0.9999        sample         44.285           ms/op
Client.getUser:getUser·p1.00          sample         44.564           ms/op
Client.listUser                       sample   4483   7.146 ± 0.102   ms/op
Client.listUser:listUser·p0.00        sample          2.675           ms/op
Client.listUser:listUser·p0.50        sample          6.717           ms/op
Client.listUser:listUser·p0.90        sample          9.676           ms/op
Client.listUser:listUser·p0.95        sample         11.043           ms/op
Client.listUser:listUser·p0.99        sample         14.896           ms/op
Client.listUser:listUser·p0.999       sample         19.516           ms/op
Client.listUser:listUser·p0.9999      sample         21.856           ms/op
Client.listUser:listUser·p1.00        sample         21.856           ms/op
