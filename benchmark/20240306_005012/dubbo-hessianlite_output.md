# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.382 ops/ms
Iteration   1: 6.005 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.005 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.873 ops/ms
Iteration   1: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.695 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ops/ms
Iteration   1: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.011 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
Iteration   1: 3.532 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.532 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.089 ms/op
Iteration   1: 3.235 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.145 ±(99.9%) 0.028 ms/op
Iteration   1: 1.839 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.881 ±(99.9%) 0.069 ms/op
Iteration   1: 3.372 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.372 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.640 ±(99.9%) 0.246 ms/op
Iteration   1: 8.071 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ±(99.9%) 0.125 ms/op
Iteration   1: 3.123 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.982 ms/op
                 createUser·p0.95:   4.289 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  10.547 ms/op
                 createUser·p0.9999: 11.639 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10248
  mean =      3.123 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1821 
    [ 2.500,  3.750) = 6954 
    [ 3.750,  5.000) = 1298 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.982 ms/op
     p(95.0000) =      4.289 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.547 ms/op
     p(99.9900) =     11.639 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.796 ±(99.9%) 0.060 ms/op
Iteration   1: 1.823 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.029 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17574
  mean =      1.823 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 550 
    [ 1.250,  2.500) = 16216 
    [ 2.500,  3.750) = 714 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.029 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.117 ms/op
Iteration   1: 3.080 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.108 ms/op
                 getUser·p0.999:  6.679 ms/op
                 getUser·p0.9999: 10.893 ms/op
                 getUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10375
  mean =      3.080 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 156 
    [ 2.000,  3.000) = 5228 
    [ 3.000,  4.000) = 4294 
    [ 4.000,  5.000) = 584 
    [ 5.000,  6.000) = 44 
    [ 6.000,  7.000) = 64 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.108 ms/op
     p(99.9000) =      6.679 ms/op
     p(99.9900) =     10.893 ms/op
     p(99.9990) =     10.928 ms/op
     p(99.9999) =     10.928 ms/op
    p(100.0000) =     10.928 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.778 ±(99.9%) 0.348 ms/op
Iteration   1: 7.840 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   3.269 ms/op
                 listUser·p0.50:   7.496 ms/op
                 listUser·p0.90:   9.978 ms/op
                 listUser·p0.95:   11.013 ms/op
                 listUser·p0.99:   15.454 ms/op
                 listUser·p0.999:  19.987 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4075
  mean =      7.840 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 86 
    [ 5.000,  7.500) = 1959 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.269 ms/op
     p(50.0000) =      7.496 ms/op
     p(90.0000) =      9.978 ms/op
     p(95.0000) =     11.013 ms/op
     p(99.0000) =     15.454 ms/op
     p(99.9000) =     19.987 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.005          ops/ms
Client.existUser                       thrpt         12.695          ops/ms
Client.getUser                         thrpt          8.011          ops/ms
Client.listUser                        thrpt          3.532          ops/ms
Client.createUser                       avgt          3.235           ms/op
Client.existUser                        avgt          1.839           ms/op
Client.getUser                          avgt          3.372           ms/op
Client.listUser                         avgt          8.071           ms/op
Client.createUser                     sample  10248   3.123 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.174           ms/op
Client.createUser:createUser·p0.50    sample          2.998           ms/op
Client.createUser:createUser·p0.90    sample          3.982           ms/op
Client.createUser:createUser·p0.95    sample          4.289           ms/op
Client.createUser:createUser·p0.99    sample          5.792           ms/op
Client.createUser:createUser·p0.999   sample         10.547           ms/op
Client.createUser:createUser·p0.9999  sample         11.639           ms/op
Client.createUser:createUser·p1.00    sample         11.665           ms/op
Client.existUser                      sample  17574   1.823 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.508           ms/op
Client.existUser:existUser·p0.50      sample          1.706           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.482           ms/op
Client.existUser:existUser·p0.99      sample          3.029           ms/op
Client.existUser:existUser·p0.999     sample         13.844           ms/op
Client.existUser:existUser·p0.9999    sample         13.943           ms/op
Client.existUser:existUser·p1.00      sample         13.943           ms/op
Client.getUser                        sample  10375   3.080 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.206           ms/op
Client.getUser:getUser·p0.50          sample          2.957           ms/op
Client.getUser:getUser·p0.90          sample          3.867           ms/op
Client.getUser:getUser·p0.95          sample          4.084           ms/op
Client.getUser:getUser·p0.99          sample          5.108           ms/op
Client.getUser:getUser·p0.999         sample          6.679           ms/op
Client.getUser:getUser·p0.9999        sample         10.893           ms/op
Client.getUser:getUser·p1.00          sample         10.928           ms/op
Client.listUser                       sample   4075   7.840 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          3.269           ms/op
Client.listUser:listUser·p0.50        sample          7.496           ms/op
Client.listUser:listUser·p0.90        sample          9.978           ms/op
Client.listUser:listUser·p0.95        sample         11.013           ms/op
Client.listUser:listUser·p0.99        sample         15.454           ms/op
Client.listUser:listUser·p0.999       sample         19.987           ms/op
Client.listUser:listUser·p0.9999      sample         24.904           ms/op
Client.listUser:listUser·p1.00        sample         24.904           ms/op
