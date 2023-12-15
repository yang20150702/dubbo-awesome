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
# Warmup Iteration   1: 1.984 ops/ms
Iteration   1: 5.162 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.162 ops/ms


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
# Warmup Iteration   1: 5.785 ops/ms
Iteration   1: 11.926 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.926 ops/ms


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
# Warmup Iteration   1: 4.525 ops/ms
Iteration   1: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.469 ops/ms


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
# Warmup Iteration   1: 2.105 ops/ms
Iteration   1: 3.077 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.077 ops/ms


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
# Warmup Iteration   1: 6.527 ±(99.9%) 0.124 ms/op
Iteration   1: 3.187 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.187 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.041 ms/op
Iteration   1: 2.001 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.001 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.054 ms/op
Iteration   1: 3.538 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.538 ms/op


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
# Warmup Iteration   1: 12.819 ±(99.9%) 0.233 ms/op
Iteration   1: 8.684 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.684 ms/op


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
# Warmup Iteration   1: 4.980 ±(99.9%) 0.099 ms/op
Iteration   1: 3.081 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.897 ms/op
                 createUser·p0.999:  19.309 ms/op
                 createUser·p0.9999: 20.743 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10368
  mean =      3.081 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2235 
    [ 2.500,  5.000) = 7860 
    [ 5.000,  7.500) = 175 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.897 ms/op
     p(99.9000) =     19.309 ms/op
     p(99.9900) =     20.743 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.107 ms/op
Iteration   1: 1.875 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   4.453 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 15.913 ms/op
                 existUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17046
  mean =      1.875 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 285 
    [ 1.250,  2.500) = 15896 
    [ 2.500,  3.750) = 663 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      4.453 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     15.913 ms/op
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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.045 ±(99.9%) 0.221 ms/op
Iteration   1: 3.206 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  6.440 ms/op
                 getUser·p0.9999: 8.356 ms/op
                 getUser·p1.00:   8.356 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9970
  mean =      3.206 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 18 
    [1.000, 1.500) = 46 
    [1.500, 2.000) = 247 
    [2.000, 2.500) = 1020 
    [2.500, 3.000) = 3359 
    [3.000, 3.500) = 2375 
    [3.500, 4.000) = 1467 
    [4.000, 4.500) = 718 
    [4.500, 5.000) = 447 
    [5.000, 5.500) = 171 
    [5.500, 6.000) = 79 
    [6.000, 6.500) = 15 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      6.440 ms/op
     p(99.9900) =      8.356 ms/op
     p(99.9990) =      8.356 ms/op
     p(99.9999) =      8.356 ms/op
    p(100.0000) =      8.356 ms/op


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
# Warmup Iteration   1: 12.669 ±(99.9%) 0.407 ms/op
Iteration   1: 8.743 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   3.510 ms/op
                 listUser·p0.50:   8.421 ms/op
                 listUser·p0.90:   10.797 ms/op
                 listUser·p0.95:   12.026 ms/op
                 listUser·p0.99:   22.631 ms/op
                 listUser·p0.999:  26.008 ms/op
                 listUser·p0.9999: 39.846 ms/op
                 listUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3658
  mean =      8.743 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 36 
    [ 5.000,  7.500) = 963 
    [ 7.500, 10.000) = 2025 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.510 ms/op
     p(50.0000) =      8.421 ms/op
     p(90.0000) =     10.797 ms/op
     p(95.0000) =     12.026 ms/op
     p(99.0000) =     22.631 ms/op
     p(99.9000) =     26.008 ms/op
     p(99.9900) =     39.846 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.162          ops/ms
Client.existUser                       thrpt         11.926          ops/ms
Client.getUser                         thrpt          9.469          ops/ms
Client.listUser                        thrpt          3.077          ops/ms
Client.createUser                       avgt          3.187           ms/op
Client.existUser                        avgt          2.001           ms/op
Client.getUser                          avgt          3.538           ms/op
Client.listUser                         avgt          8.684           ms/op
Client.createUser                     sample  10368   3.081 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.028           ms/op
Client.createUser:createUser·p0.50    sample          2.879           ms/op
Client.createUser:createUser·p0.90    sample          4.178           ms/op
Client.createUser:createUser·p0.95    sample          4.579           ms/op
Client.createUser:createUser·p0.99    sample          6.897           ms/op
Client.createUser:createUser·p0.999   sample         19.309           ms/op
Client.createUser:createUser·p0.9999  sample         20.743           ms/op
Client.createUser:createUser·p1.00    sample         20.775           ms/op
Client.existUser                      sample  17046   1.875 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.509           ms/op
Client.existUser:existUser·p0.50      sample          1.733           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.507           ms/op
Client.existUser:existUser·p0.99      sample          4.453           ms/op
Client.existUser:existUser·p0.999     sample         15.778           ms/op
Client.existUser:existUser·p0.9999    sample         15.913           ms/op
Client.existUser:existUser·p1.00      sample         16.040           ms/op
Client.getUser                        sample   9970   3.206 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.605           ms/op
Client.getUser:getUser·p0.50          sample          3.043           ms/op
Client.getUser:getUser·p0.90          sample          4.260           ms/op
Client.getUser:getUser·p0.95          sample          4.719           ms/op
Client.getUser:getUser·p0.99          sample          5.521           ms/op
Client.getUser:getUser·p0.999         sample          6.440           ms/op
Client.getUser:getUser·p0.9999        sample          8.356           ms/op
Client.getUser:getUser·p1.00          sample          8.356           ms/op
Client.listUser                       sample   3658   8.743 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          3.510           ms/op
Client.listUser:listUser·p0.50        sample          8.421           ms/op
Client.listUser:listUser·p0.90        sample         10.797           ms/op
Client.listUser:listUser·p0.95        sample         12.026           ms/op
Client.listUser:listUser·p0.99        sample         22.631           ms/op
Client.listUser:listUser·p0.999       sample         26.008           ms/op
Client.listUser:listUser·p0.9999      sample         39.846           ms/op
Client.listUser:listUser·p1.00        sample         39.846           ms/op
