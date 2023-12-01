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
# Warmup Iteration   1: 2.451 ops/ms
Iteration   1: 5.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.395 ops/ms


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
# Warmup Iteration   1: 6.023 ops/ms
Iteration   1: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.761 ops/ms


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
# Warmup Iteration   1: 4.620 ops/ms
Iteration   1: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.551 ops/ms


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
# Warmup Iteration   1: 2.079 ops/ms
Iteration   1: 3.369 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.369 ops/ms


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.056 ms/op
Iteration   1: 3.046 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.046 ms/op


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
# Warmup Iteration   1: 2.899 ±(99.9%) 0.030 ms/op
Iteration   1: 1.724 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.724 ms/op


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
# Warmup Iteration   1: 4.890 ±(99.9%) 0.064 ms/op
Iteration   1: 3.036 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.036 ms/op


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
# Warmup Iteration   1: 11.762 ±(99.9%) 0.238 ms/op
Iteration   1: 7.575 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.575 ms/op


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.120 ms/op
Iteration   1: 2.709 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  11.856 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11785
  mean =      2.709 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 5137 
    [ 2.500,  3.750) = 5955 
    [ 3.750,  5.000) = 537 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     11.856 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.061 ms/op
Iteration   1: 1.797 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   2.880 ms/op
                 existUser·p0.999:  16.039 ms/op
                 existUser·p0.9999: 17.210 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17787
  mean =      1.797 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 759 
    [ 1.250,  2.500) = 16561 
    [ 2.500,  3.750) = 383 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      2.880 ms/op
     p(99.9000) =     16.039 ms/op
     p(99.9900) =     17.210 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.101 ms/op
Iteration   1: 3.091 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.812 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 34.822 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10347
  mean =      3.091 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2954 
    [ 2.500,  5.000) = 7100 
    [ 5.000,  7.500) = 229 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.812 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     34.822 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 13.315 ±(99.9%) 0.454 ms/op
Iteration   1: 7.543 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   7.209 ms/op
                 listUser·p0.90:   9.929 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   14.385 ms/op
                 listUser·p0.999:  20.398 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4249
  mean =      7.543 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 214 
    [ 5.000,  7.500) = 2208 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      7.209 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     11.158 ms/op
     p(99.0000) =     14.385 ms/op
     p(99.9000) =     20.398 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.395          ops/ms
Client.existUser                       thrpt         12.761          ops/ms
Client.getUser                         thrpt          8.551          ops/ms
Client.listUser                        thrpt          3.369          ops/ms
Client.createUser                       avgt          3.046           ms/op
Client.existUser                        avgt          1.724           ms/op
Client.getUser                          avgt          3.036           ms/op
Client.listUser                         avgt          7.575           ms/op
Client.createUser                     sample  11785   2.709 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          0.991           ms/op
Client.createUser:createUser·p0.50    sample          2.572           ms/op
Client.createUser:createUser·p0.90    sample          3.387           ms/op
Client.createUser:createUser·p0.95    sample          3.875           ms/op
Client.createUser:createUser·p0.99    sample          5.259           ms/op
Client.createUser:createUser·p0.999   sample         11.856           ms/op
Client.createUser:createUser·p0.9999  sample         12.665           ms/op
Client.createUser:createUser·p1.00    sample         12.665           ms/op
Client.existUser                      sample  17787   1.797 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.567           ms/op
Client.existUser:existUser·p0.50      sample          1.763           ms/op
Client.existUser:existUser·p0.90      sample          2.126           ms/op
Client.existUser:existUser·p0.95      sample          2.302           ms/op
Client.existUser:existUser·p0.99      sample          2.880           ms/op
Client.existUser:existUser·p0.999     sample         16.039           ms/op
Client.existUser:existUser·p0.9999    sample         17.210           ms/op
Client.existUser:existUser·p1.00      sample         17.465           ms/op
Client.getUser                        sample  10347   3.091 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.765           ms/op
Client.getUser:getUser·p0.50          sample          2.900           ms/op
Client.getUser:getUser·p0.90          sample          3.895           ms/op
Client.getUser:getUser·p0.95          sample          4.506           ms/op
Client.getUser:getUser·p0.99          sample          6.812           ms/op
Client.getUser:getUser·p0.999         sample         23.495           ms/op
Client.getUser:getUser·p0.9999        sample         34.822           ms/op
Client.getUser:getUser·p1.00          sample         34.931           ms/op
Client.listUser                       sample   4249   7.543 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.830           ms/op
Client.listUser:listUser·p0.50        sample          7.209           ms/op
Client.listUser:listUser·p0.90        sample          9.929           ms/op
Client.listUser:listUser·p0.95        sample         11.158           ms/op
Client.listUser:listUser·p0.99        sample         14.385           ms/op
Client.listUser:listUser·p0.999       sample         20.398           ms/op
Client.listUser:listUser·p0.9999      sample         21.037           ms/op
Client.listUser:listUser·p1.00        sample         21.037           ms/op
