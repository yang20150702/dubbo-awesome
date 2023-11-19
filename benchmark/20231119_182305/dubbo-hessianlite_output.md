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
# Warmup Iteration   1: 2.381 ops/ms
Iteration   1: 6.201 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.201 ops/ms


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
# Warmup Iteration   1: 6.041 ops/ms
Iteration   1: 13.329 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.329 ops/ms


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
# Warmup Iteration   1: 4.403 ops/ms
Iteration   1: 8.748 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.748 ops/ms


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
# Warmup Iteration   1: 2.089 ops/ms
Iteration   1: 3.527 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.527 ops/ms


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
# Warmup Iteration   1: 5.176 ±(99.9%) 0.067 ms/op
Iteration   1: 3.278 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.278 ms/op


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
# Warmup Iteration   1: 3.456 ±(99.9%) 0.049 ms/op
Iteration   1: 1.787 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.049 ms/op
Iteration   1: 3.138 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.138 ms/op


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
# Warmup Iteration   1: 12.460 ±(99.9%) 0.269 ms/op
Iteration   1: 8.605 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.605 ms/op


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
# Warmup Iteration   1: 5.286 ±(99.9%) 0.168 ms/op
Iteration   1: 3.045 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  14.655 ms/op
                 createUser·p0.9999: 14.728 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10502
  mean =      3.045 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3479 
    [ 2.500,  3.750) = 5758 
    [ 3.750,  5.000) = 773 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     14.655 ms/op
     p(99.9900) =     14.728 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 2.782 ±(99.9%) 0.052 ms/op
Iteration   1: 2.073 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.374 ms/op
                 existUser·p0.50:   2.025 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  15.032 ms/op
                 existUser·p0.9999: 15.326 ms/op
                 existUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15489
  mean =      2.073 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 12483 
    [ 2.500,  3.750) = 2387 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     15.032 ms/op
     p(99.9900) =     15.326 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.111 ms/op
Iteration   1: 2.985 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.494 ms/op
                 getUser·p0.999:  22.741 ms/op
                 getUser·p0.9999: 24.917 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10717
  mean =      2.985 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3080 
    [ 2.500,  5.000) = 7496 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.494 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     24.917 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 11.834 ±(99.9%) 0.520 ms/op
Iteration   1: 8.628 ±(99.9%) 0.141 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   8.192 ms/op
                 listUser·p0.90:   11.469 ms/op
                 listUser·p0.95:   12.691 ms/op
                 listUser·p0.99:   20.480 ms/op
                 listUser·p0.999:  23.159 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3707
  mean =      8.628 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 112 
    [ 5.000,  7.500) = 1130 
    [ 7.500, 10.000) = 1672 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      8.192 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     12.691 ms/op
     p(99.0000) =     20.480 ms/op
     p(99.9000) =     23.159 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.201          ops/ms
Client.existUser                       thrpt         13.329          ops/ms
Client.getUser                         thrpt          8.748          ops/ms
Client.listUser                        thrpt          3.527          ops/ms
Client.createUser                       avgt          3.278           ms/op
Client.existUser                        avgt          1.787           ms/op
Client.getUser                          avgt          3.138           ms/op
Client.listUser                         avgt          8.605           ms/op
Client.createUser                     sample  10502   3.045 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.313           ms/op
Client.createUser:createUser·p0.50    sample          2.712           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.628           ms/op
Client.createUser:createUser·p0.99    sample         10.306           ms/op
Client.createUser:createUser·p0.999   sample         14.655           ms/op
Client.createUser:createUser·p0.9999  sample         14.728           ms/op
Client.createUser:createUser·p1.00    sample         14.729           ms/op
Client.existUser                      sample  15489   2.073 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.374           ms/op
Client.existUser:existUser·p0.50      sample          2.025           ms/op
Client.existUser:existUser·p0.90      sample          2.650           ms/op
Client.existUser:existUser·p0.95      sample          2.912           ms/op
Client.existUser:existUser·p0.99      sample          3.432           ms/op
Client.existUser:existUser·p0.999     sample         15.032           ms/op
Client.existUser:existUser·p0.9999    sample         15.326           ms/op
Client.existUser:existUser·p1.00      sample         15.335           ms/op
Client.getUser                        sample  10717   2.985 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.655           ms/op
Client.getUser:getUser·p0.50          sample          2.929           ms/op
Client.getUser:getUser·p0.90          sample          3.707           ms/op
Client.getUser:getUser·p0.95          sample          3.998           ms/op
Client.getUser:getUser·p0.99          sample          5.494           ms/op
Client.getUser:getUser·p0.999         sample         22.741           ms/op
Client.getUser:getUser·p0.9999        sample         24.917           ms/op
Client.getUser:getUser·p1.00          sample         25.035           ms/op
Client.listUser                       sample   3707   8.628 ± 0.141   ms/op
Client.listUser:listUser·p0.00        sample          1.843           ms/op
Client.listUser:listUser·p0.50        sample          8.192           ms/op
Client.listUser:listUser·p0.90        sample         11.469           ms/op
Client.listUser:listUser·p0.95        sample         12.691           ms/op
Client.listUser:listUser·p0.99        sample         20.480           ms/op
Client.listUser:listUser·p0.999       sample         23.159           ms/op
Client.listUser:listUser·p0.9999      sample         26.870           ms/op
Client.listUser:listUser·p1.00        sample         26.870           ms/op
