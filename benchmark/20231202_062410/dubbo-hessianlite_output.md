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
# Warmup Iteration   1: 2.346 ops/ms
Iteration   1: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.789 ops/ms


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
# Warmup Iteration   1: 5.922 ops/ms
Iteration   1: 14.333 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.333 ops/ms


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
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.563 ops/ms


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
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 3.539 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.539 ops/ms


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
# Warmup Iteration   1: 4.995 ±(99.9%) 0.081 ms/op
Iteration   1: 3.165 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.165 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.034 ms/op
Iteration   1: 1.809 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.809 ms/op


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.070 ms/op
Iteration   1: 3.482 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.482 ms/op


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
# Warmup Iteration   1: 13.606 ±(99.9%) 0.273 ms/op
Iteration   1: 8.558 ±(99.9%) 0.143 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.558 ms/op


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
# Warmup Iteration   1: 5.118 ±(99.9%) 0.123 ms/op
Iteration   1: 3.223 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   4.034 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   8.297 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 21.135 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9920
  mean =      3.223 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1992 
    [ 2.500,  5.000) = 7541 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.034 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      8.297 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.079 ms/op
Iteration   1: 1.840 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.190 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 6.367 ms/op
                 existUser·p1.00:   6.373 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17568
  mean =      1.840 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 18 
    [1.000, 1.500) = 3914 
    [1.500, 2.000) = 7754 
    [2.000, 2.500) = 5175 
    [2.500, 3.000) = 402 
    [3.000, 3.500) = 170 
    [3.500, 4.000) = 51 
    [4.000, 4.500) = 46 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.190 ms/op
     p(99.9000) =      6.119 ms/op
     p(99.9900) =      6.367 ms/op
     p(99.9990) =      6.373 ms/op
     p(99.9999) =      6.373 ms/op
    p(100.0000) =      6.373 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.088 ms/op
Iteration   1: 2.848 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.350 ms/op
                 getUser·p0.999:  25.821 ms/op
                 getUser·p0.9999: 27.228 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11221
  mean =      2.848 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4733 
    [ 2.500,  5.000) = 6319 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.350 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     27.228 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 13.065 ±(99.9%) 0.496 ms/op
Iteration   1: 8.699 ±(99.9%) 0.143 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   8.225 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.878 ms/op
                 listUser·p0.99:   20.202 ms/op
                 listUser·p0.999:  24.266 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3747
  mean =      8.699 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 75 
    [ 5.000,  7.500) = 1093 
    [ 7.500, 10.000) = 1785 
    [10.000, 12.500) = 580 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.441 ms/op
     p(50.0000) =      8.225 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.878 ms/op
     p(99.0000) =     20.202 ms/op
     p(99.9000) =     24.266 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.789          ops/ms
Client.existUser                       thrpt         14.333          ops/ms
Client.getUser                         thrpt          8.563          ops/ms
Client.listUser                        thrpt          3.539          ops/ms
Client.createUser                       avgt          3.165           ms/op
Client.existUser                        avgt          1.809           ms/op
Client.getUser                          avgt          3.482           ms/op
Client.listUser                         avgt          8.558           ms/op
Client.createUser                     sample   9920   3.223 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          0.871           ms/op
Client.createUser:createUser·p0.50    sample          3.015           ms/op
Client.createUser:createUser·p0.90    sample          4.034           ms/op
Client.createUser:createUser·p0.95    sample          4.653           ms/op
Client.createUser:createUser·p0.99    sample          8.297           ms/op
Client.createUser:createUser·p0.999   sample         20.873           ms/op
Client.createUser:createUser·p0.9999  sample         21.135           ms/op
Client.createUser:createUser·p1.00    sample         21.135           ms/op
Client.existUser                      sample  17568   1.840 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.404           ms/op
Client.existUser:existUser·p0.50      sample          1.761           ms/op
Client.existUser:existUser·p0.90      sample          2.306           ms/op
Client.existUser:existUser·p0.95      sample          2.441           ms/op
Client.existUser:existUser·p0.99      sample          3.190           ms/op
Client.existUser:existUser·p0.999     sample          6.119           ms/op
Client.existUser:existUser·p0.9999    sample          6.367           ms/op
Client.existUser:existUser·p1.00      sample          6.373           ms/op
Client.getUser                        sample  11221   2.848 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          0.645           ms/op
Client.getUser:getUser·p0.50          sample          2.626           ms/op
Client.getUser:getUser·p0.90          sample          3.740           ms/op
Client.getUser:getUser·p0.95          sample          4.014           ms/op
Client.getUser:getUser·p0.99          sample          5.350           ms/op
Client.getUser:getUser·p0.999         sample         25.821           ms/op
Client.getUser:getUser·p0.9999        sample         27.228           ms/op
Client.getUser:getUser·p1.00          sample         27.296           ms/op
Client.listUser                       sample   3747   8.699 ± 0.143   ms/op
Client.listUser:listUser·p0.00        sample          2.441           ms/op
Client.listUser:listUser·p0.50        sample          8.225           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.878           ms/op
Client.listUser:listUser·p0.99        sample         20.202           ms/op
Client.listUser:listUser·p0.999       sample         24.266           ms/op
Client.listUser:listUser·p0.9999      sample         31.064           ms/op
Client.listUser:listUser·p1.00        sample         31.064           ms/op
