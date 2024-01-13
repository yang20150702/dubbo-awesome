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
# Warmup Iteration   1: 2.237 ops/ms
Iteration   1: 6.225 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.225 ops/ms


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
# Warmup Iteration   1: 6.546 ops/ms
Iteration   1: 13.404 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.404 ops/ms


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
# Warmup Iteration   1: 4.252 ops/ms
Iteration   1: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.859 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
Iteration   1: 3.638 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.638 ops/ms


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
# Warmup Iteration   1: 5.450 ±(99.9%) 0.063 ms/op
Iteration   1: 3.485 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.485 ms/op


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
# Warmup Iteration   1: 3.167 ±(99.9%) 0.033 ms/op
Iteration   1: 2.025 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.025 ms/op


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
# Warmup Iteration   1: 5.857 ±(99.9%) 0.064 ms/op
Iteration   1: 3.248 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.248 ms/op


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
# Warmup Iteration   1: 13.628 ±(99.9%) 0.262 ms/op
Iteration   1: 8.839 ±(99.9%) 0.108 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.839 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.115 ms/op
Iteration   1: 3.129 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   7.019 ms/op
                 createUser·p0.999:  16.757 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10208
  mean =      3.129 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1116 
    [ 2.500,  3.750) = 8087 
    [ 3.750,  5.000) = 622 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.019 ms/op
     p(99.9000) =     16.757 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.103 ms/op
Iteration   1: 1.862 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  9.721 ms/op
                 existUser·p0.9999: 10.265 ms/op
                 existUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17700
  mean =      1.862 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 16398 
    [ 2.500,  3.750) = 839 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.371 ms/op
     p(99.9000) =      9.721 ms/op
     p(99.9900) =     10.265 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.098 ms/op
Iteration   1: 2.892 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.773 ms/op
                 getUser·p0.90:   3.856 ms/op
                 getUser·p0.95:   4.364 ms/op
                 getUser·p0.99:   5.278 ms/op
                 getUser·p0.999:  6.872 ms/op
                 getUser·p0.9999: 8.387 ms/op
                 getUser·p1.00:   8.389 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11065
  mean =      2.892 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 12 
    [1.000, 1.500) = 114 
    [1.500, 2.000) = 580 
    [2.000, 2.500) = 2986 
    [2.500, 3.000) = 3168 
    [3.000, 3.500) = 2318 
    [3.500, 4.000) = 1007 
    [4.000, 4.500) = 426 
    [4.500, 5.000) = 243 
    [5.000, 5.500) = 132 
    [5.500, 6.000) = 54 
    [6.000, 6.500) = 10 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.856 ms/op
     p(95.0000) =      4.364 ms/op
     p(99.0000) =      5.278 ms/op
     p(99.9000) =      6.872 ms/op
     p(99.9900) =      8.387 ms/op
     p(99.9990) =      8.389 ms/op
     p(99.9999) =      8.389 ms/op
    p(100.0000) =      8.389 ms/op


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
# Warmup Iteration   1: 13.975 ±(99.9%) 0.499 ms/op
Iteration   1: 7.978 ±(99.9%) 0.104 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   7.700 ms/op
                 listUser·p0.90:   10.102 ms/op
                 listUser·p0.95:   11.285 ms/op
                 listUser·p0.99:   15.626 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4003
  mean =      7.978 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 82 
    [ 5.000,  7.500) = 1692 
    [ 7.500, 10.000) = 1810 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      7.700 ms/op
     p(90.0000) =     10.102 ms/op
     p(95.0000) =     11.285 ms/op
     p(99.0000) =     15.626 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.225          ops/ms
Client.existUser                       thrpt         13.404          ops/ms
Client.getUser                         thrpt          7.859          ops/ms
Client.listUser                        thrpt          3.638          ops/ms
Client.createUser                       avgt          3.485           ms/op
Client.existUser                        avgt          2.025           ms/op
Client.getUser                          avgt          3.248           ms/op
Client.listUser                         avgt          8.839           ms/op
Client.createUser                     sample  10208   3.129 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          0.926           ms/op
Client.createUser:createUser·p0.50    sample          2.896           ms/op
Client.createUser:createUser·p0.90    sample          3.740           ms/op
Client.createUser:createUser·p0.95    sample          4.604           ms/op
Client.createUser:createUser·p0.99    sample          7.019           ms/op
Client.createUser:createUser·p0.999   sample         16.757           ms/op
Client.createUser:createUser·p0.9999  sample         17.302           ms/op
Client.createUser:createUser·p1.00    sample         17.302           ms/op
Client.existUser                      sample  17700   1.862 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.786           ms/op
Client.existUser:existUser·p0.50      sample          1.759           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.371           ms/op
Client.existUser:existUser·p0.999     sample          9.721           ms/op
Client.existUser:existUser·p0.9999    sample         10.265           ms/op
Client.existUser:existUser·p1.00      sample         11.502           ms/op
Client.getUser                        sample  11065   2.892 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.787           ms/op
Client.getUser:getUser·p0.50          sample          2.773           ms/op
Client.getUser:getUser·p0.90          sample          3.856           ms/op
Client.getUser:getUser·p0.95          sample          4.364           ms/op
Client.getUser:getUser·p0.99          sample          5.278           ms/op
Client.getUser:getUser·p0.999         sample          6.872           ms/op
Client.getUser:getUser·p0.9999        sample          8.387           ms/op
Client.getUser:getUser·p1.00          sample          8.389           ms/op
Client.listUser                       sample   4003   7.978 ± 0.104   ms/op
Client.listUser:listUser·p0.00        sample          2.269           ms/op
Client.listUser:listUser·p0.50        sample          7.700           ms/op
Client.listUser:listUser·p0.90        sample         10.102           ms/op
Client.listUser:listUser·p0.95        sample         11.285           ms/op
Client.listUser:listUser·p0.99        sample         15.626           ms/op
Client.listUser:listUser·p0.999       sample         20.087           ms/op
Client.listUser:listUser·p0.9999      sample         20.218           ms/op
Client.listUser:listUser·p1.00        sample         20.218           ms/op
