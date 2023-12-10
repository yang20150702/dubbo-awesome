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
# Warmup Iteration   1: 2.463 ops/ms
Iteration   1: 6.969 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.969 ops/ms


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
# Warmup Iteration   1: 6.847 ops/ms
Iteration   1: 13.690 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.690 ops/ms


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
# Warmup Iteration   1: 4.274 ops/ms
Iteration   1: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.575 ops/ms


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
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 3.849 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.849 ops/ms


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
# Warmup Iteration   1: 5.706 ±(99.9%) 0.089 ms/op
Iteration   1: 3.132 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.132 ms/op


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
# Warmup Iteration   1: 3.430 ±(99.9%) 0.039 ms/op
Iteration   1: 1.872 ±(99.9%) 0.018 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ±(99.9%) 0.046 ms/op
Iteration   1: 2.966 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.966 ms/op


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
# Warmup Iteration   1: 12.219 ±(99.9%) 0.237 ms/op
Iteration   1: 9.240 ±(99.9%) 0.119 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.240 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.103 ms/op
Iteration   1: 3.299 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   12.452 ms/op
                 createUser·p0.999:  20.391 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9708
  mean =      3.299 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1710 
    [ 2.500,  5.000) = 7663 
    [ 5.000,  7.500) = 143 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     20.391 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.080 ms/op
Iteration   1: 1.836 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  7.509 ms/op
                 existUser·p0.9999: 11.854 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17426
  mean =      1.836 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 623 
    [ 1.250,  2.500) = 15824 
    [ 2.500,  3.750) = 774 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      7.509 ms/op
     p(99.9900) =     11.854 ms/op
     p(99.9990) =     11.878 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.111 ms/op
Iteration   1: 3.441 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.690 ms/op
                 getUser·p0.99:   6.142 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9310
  mean =      3.441 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1291 
    [ 2.500,  3.750) = 5332 
    [ 3.750,  5.000) = 2414 
    [ 5.000,  6.250) = 189 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.690 ms/op
     p(99.0000) =      6.142 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 12.047 ±(99.9%) 0.402 ms/op
Iteration   1: 9.084 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   3.170 ms/op
                 listUser·p0.50:   8.733 ms/op
                 listUser·p0.90:   12.124 ms/op
                 listUser·p0.95:   13.623 ms/op
                 listUser·p0.99:   15.376 ms/op
                 listUser·p0.999:  19.291 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3549
  mean =      9.084 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 52 
    [ 5.000,  7.500) = 735 
    [ 7.500, 10.000) = 1828 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.170 ms/op
     p(50.0000) =      8.733 ms/op
     p(90.0000) =     12.124 ms/op
     p(95.0000) =     13.623 ms/op
     p(99.0000) =     15.376 ms/op
     p(99.9000) =     19.291 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.969          ops/ms
Client.existUser                       thrpt         13.690          ops/ms
Client.getUser                         thrpt          7.575          ops/ms
Client.listUser                        thrpt          3.849          ops/ms
Client.createUser                       avgt          3.132           ms/op
Client.existUser                        avgt          1.872           ms/op
Client.getUser                          avgt          2.966           ms/op
Client.listUser                         avgt          9.240           ms/op
Client.createUser                     sample   9708   3.299 ± 0.060   ms/op
Client.createUser:createUser·p0.00    sample          0.824           ms/op
Client.createUser:createUser·p0.50    sample          2.904           ms/op
Client.createUser:createUser·p0.90    sample          4.162           ms/op
Client.createUser:createUser·p0.95    sample          4.522           ms/op
Client.createUser:createUser·p0.99    sample         12.452           ms/op
Client.createUser:createUser·p0.999   sample         20.391           ms/op
Client.createUser:createUser·p0.9999  sample         20.840           ms/op
Client.createUser:createUser·p1.00    sample         20.840           ms/op
Client.existUser                      sample  17426   1.836 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.516           ms/op
Client.existUser:existUser·p0.50      sample          1.749           ms/op
Client.existUser:existUser·p0.90      sample          2.322           ms/op
Client.existUser:existUser·p0.95      sample          2.564           ms/op
Client.existUser:existUser·p0.99      sample          3.838           ms/op
Client.existUser:existUser·p0.999     sample          7.509           ms/op
Client.existUser:existUser·p0.9999    sample         11.854           ms/op
Client.existUser:existUser·p1.00      sample         11.878           ms/op
Client.getUser                        sample   9310   3.441 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.693           ms/op
Client.getUser:getUser·p0.50          sample          3.383           ms/op
Client.getUser:getUser·p0.90          sample          4.350           ms/op
Client.getUser:getUser·p0.95          sample          4.690           ms/op
Client.getUser:getUser·p0.99          sample          6.142           ms/op
Client.getUser:getUser·p0.999         sample         17.138           ms/op
Client.getUser:getUser·p0.9999        sample         17.170           ms/op
Client.getUser:getUser·p1.00          sample         17.170           ms/op
Client.listUser                       sample   3549   9.084 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          3.170           ms/op
Client.listUser:listUser·p0.50        sample          8.733           ms/op
Client.listUser:listUser·p0.90        sample         12.124           ms/op
Client.listUser:listUser·p0.95        sample         13.623           ms/op
Client.listUser:listUser·p0.99        sample         15.376           ms/op
Client.listUser:listUser·p0.999       sample         19.291           ms/op
Client.listUser:listUser·p0.9999      sample         23.134           ms/op
Client.listUser:listUser·p1.00        sample         23.134           ms/op
