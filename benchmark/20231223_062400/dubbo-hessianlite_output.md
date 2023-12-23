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
# Warmup Iteration   1: 2.178 ops/ms
Iteration   1: 5.887 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.887 ops/ms


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
# Warmup Iteration   1: 5.971 ops/ms
Iteration   1: 13.471 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.471 ops/ms


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
# Warmup Iteration   1: 4.196 ops/ms
Iteration   1: 8.059 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.059 ops/ms


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
# Warmup Iteration   1: 2.142 ops/ms
Iteration   1: 3.601 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.601 ops/ms


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
# Warmup Iteration   1: 5.927 ±(99.9%) 0.082 ms/op
Iteration   1: 3.110 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.110 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.030 ms/op
Iteration   1: 1.836 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.836 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.049 ms/op
Iteration   1: 3.408 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.408 ms/op


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
# Warmup Iteration   1: 13.126 ±(99.9%) 0.245 ms/op
Iteration   1: 8.327 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.327 ms/op


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
# Warmup Iteration   1: 5.381 ±(99.9%) 0.141 ms/op
Iteration   1: 3.038 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   2.843 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   4.302 ms/op
                 createUser·p0.99:   7.268 ms/op
                 createUser·p0.999:  15.598 ms/op
                 createUser·p0.9999: 16.312 ms/op
                 createUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10677
  mean =      3.038 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1456 
    [ 2.500,  3.750) = 8385 
    [ 3.750,  5.000) = 546 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      4.302 ms/op
     p(99.0000) =      7.268 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     16.312 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.066 ms/op
Iteration   1: 1.803 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   3.189 ms/op
                 existUser·p0.999:  17.269 ms/op
                 existUser·p0.9999: 17.452 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17740
  mean =      1.803 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 212 
    [ 1.250,  2.500) = 16972 
    [ 2.500,  3.750) = 409 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      3.189 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.452 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.112 ms/op
Iteration   1: 3.111 ±(99.9%) 0.087 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  52.625 ms/op
                 getUser·p0.9999: 56.061 ms/op
                 getUser·p1.00:   56.164 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10478
  mean =      3.111 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10346 
    [ 5.000, 10.000) = 96 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     52.625 ms/op
     p(99.9900) =     56.061 ms/op
     p(99.9990) =     56.164 ms/op
     p(99.9999) =     56.164 ms/op
    p(100.0000) =     56.164 ms/op


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
# Warmup Iteration   1: 12.747 ±(99.9%) 0.428 ms/op
Iteration   1: 8.053 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   7.668 ms/op
                 listUser·p0.90:   10.523 ms/op
                 listUser·p0.95:   11.813 ms/op
                 listUser·p0.99:   16.949 ms/op
                 listUser·p0.999:  28.580 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3976
  mean =      8.053 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 154 
    [ 5.000,  7.500) = 1681 
    [ 7.500, 10.000) = 1595 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      7.668 ms/op
     p(90.0000) =     10.523 ms/op
     p(95.0000) =     11.813 ms/op
     p(99.0000) =     16.949 ms/op
     p(99.9000) =     28.580 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.887          ops/ms
Client.existUser                       thrpt         13.471          ops/ms
Client.getUser                         thrpt          8.059          ops/ms
Client.listUser                        thrpt          3.601          ops/ms
Client.createUser                       avgt          3.110           ms/op
Client.existUser                        avgt          1.836           ms/op
Client.getUser                          avgt          3.408           ms/op
Client.listUser                         avgt          8.327           ms/op
Client.createUser                     sample  10677   3.038 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.270           ms/op
Client.createUser:createUser·p0.50    sample          2.843           ms/op
Client.createUser:createUser·p0.90    sample          3.543           ms/op
Client.createUser:createUser·p0.95    sample          4.302           ms/op
Client.createUser:createUser·p0.99    sample          7.268           ms/op
Client.createUser:createUser·p0.999   sample         15.598           ms/op
Client.createUser:createUser·p0.9999  sample         16.312           ms/op
Client.createUser:createUser·p1.00    sample         16.318           ms/op
Client.existUser                      sample  17740   1.803 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.547           ms/op
Client.existUser:existUser·p0.50      sample          1.683           ms/op
Client.existUser:existUser·p0.90      sample          2.134           ms/op
Client.existUser:existUser·p0.95      sample          2.322           ms/op
Client.existUser:existUser·p0.99      sample          3.189           ms/op
Client.existUser:existUser·p0.999     sample         17.269           ms/op
Client.existUser:existUser·p0.9999    sample         17.452           ms/op
Client.existUser:existUser·p1.00      sample         17.629           ms/op
Client.getUser                        sample  10478   3.111 ± 0.087   ms/op
Client.getUser:getUser·p0.00          sample          0.629           ms/op
Client.getUser:getUser·p0.50          sample          2.916           ms/op
Client.getUser:getUser·p0.90          sample          3.686           ms/op
Client.getUser:getUser·p0.95          sample          3.990           ms/op
Client.getUser:getUser·p0.99          sample          5.186           ms/op
Client.getUser:getUser·p0.999         sample         52.625           ms/op
Client.getUser:getUser·p0.9999        sample         56.061           ms/op
Client.getUser:getUser·p1.00          sample         56.164           ms/op
Client.listUser                       sample   3976   8.053 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          2.245           ms/op
Client.listUser:listUser·p0.50        sample          7.668           ms/op
Client.listUser:listUser·p0.90        sample         10.523           ms/op
Client.listUser:listUser·p0.95        sample         11.813           ms/op
Client.listUser:listUser·p0.99        sample         16.949           ms/op
Client.listUser:listUser·p0.999       sample         28.580           ms/op
Client.listUser:listUser·p0.9999      sample         34.275           ms/op
Client.listUser:listUser·p1.00        sample         34.275           ms/op
