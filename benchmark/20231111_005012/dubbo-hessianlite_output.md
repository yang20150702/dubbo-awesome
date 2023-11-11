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
# Warmup Iteration   1: 2.478 ops/ms
Iteration   1: 6.305 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.305 ops/ms


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
# Warmup Iteration   1: 6.393 ops/ms
Iteration   1: 11.861 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.861 ops/ms


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
# Warmup Iteration   1: 4.791 ops/ms
Iteration   1: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.572 ops/ms


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
# Warmup Iteration   1: 1.959 ops/ms
Iteration   1: 3.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.463 ops/ms


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.055 ms/op
Iteration   1: 3.195 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.195 ms/op


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
# Warmup Iteration   1: 3.377 ±(99.9%) 0.038 ms/op
Iteration   1: 1.877 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.048 ms/op
Iteration   1: 2.847 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.847 ms/op


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
# Warmup Iteration   1: 12.536 ±(99.9%) 0.218 ms/op
Iteration   1: 7.964 ±(99.9%) 0.065 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.964 ms/op


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.115 ms/op
Iteration   1: 3.105 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10494
  mean =      3.105 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3253 
    [ 2.500,  5.000) = 6963 
    [ 5.000,  7.500) = 189 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.049 ms/op
Iteration   1: 2.083 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.040 ms/op
                 existUser·p0.90:   2.436 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.725 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15451
  mean =      2.083 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 13946 
    [ 2.500,  3.750) = 987 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.436 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.725 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.084 ms/op
Iteration   1: 3.280 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 10.502 ms/op
                 getUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9820
  mean =      3.280 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 97 
    [ 2.000,  3.000) = 3617 
    [ 3.000,  4.000) = 4859 
    [ 4.000,  5.000) = 1078 
    [ 5.000,  6.000) = 130 
    [ 6.000,  7.000) = 6 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 15 
    [ 9.000, 10.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     10.502 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


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
# Warmup Iteration   1: 10.973 ±(99.9%) 0.326 ms/op
Iteration   1: 7.914 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   7.684 ms/op
                 listUser·p0.90:   10.404 ms/op
                 listUser·p0.95:   11.190 ms/op
                 listUser·p0.99:   14.662 ms/op
                 listUser·p0.999:  18.092 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4071
  mean =      7.914 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 14 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 1114 
    [ 7.500,  8.750) = 1109 
    [ 8.750, 10.000) = 590 
    [10.000, 11.250) = 332 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =     10.404 ms/op
     p(95.0000) =     11.190 ms/op
     p(99.0000) =     14.662 ms/op
     p(99.9000) =     18.092 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.305          ops/ms
Client.existUser                       thrpt         11.861          ops/ms
Client.getUser                         thrpt          9.572          ops/ms
Client.listUser                        thrpt          3.463          ops/ms
Client.createUser                       avgt          3.195           ms/op
Client.existUser                        avgt          1.877           ms/op
Client.getUser                          avgt          2.847           ms/op
Client.listUser                         avgt          7.964           ms/op
Client.createUser                     sample  10494   3.105 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.319           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          4.067           ms/op
Client.createUser:createUser·p0.95    sample          4.391           ms/op
Client.createUser:createUser·p0.99    sample          7.029           ms/op
Client.createUser:createUser·p0.999   sample         20.840           ms/op
Client.createUser:createUser·p0.9999  sample         21.004           ms/op
Client.createUser:createUser·p1.00    sample         21.004           ms/op
Client.existUser                      sample  15451   2.083 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.486           ms/op
Client.existUser:existUser·p0.50      sample          2.040           ms/op
Client.existUser:existUser·p0.90      sample          2.436           ms/op
Client.existUser:existUser·p0.95      sample          2.605           ms/op
Client.existUser:existUser·p0.99      sample          3.725           ms/op
Client.existUser:existUser·p0.999     sample         17.924           ms/op
Client.existUser:existUser·p0.9999    sample         18.940           ms/op
Client.existUser:existUser·p1.00      sample         18.940           ms/op
Client.getUser                        sample   9820   3.280 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.599           ms/op
Client.getUser:getUser·p0.50          sample          3.191           ms/op
Client.getUser:getUser·p0.90          sample          4.133           ms/op
Client.getUser:getUser·p0.95          sample          4.506           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample         10.322           ms/op
Client.getUser:getUser·p0.9999        sample         10.502           ms/op
Client.getUser:getUser·p1.00          sample         10.502           ms/op
Client.listUser                       sample   4071   7.914 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          2.523           ms/op
Client.listUser:listUser·p0.50        sample          7.684           ms/op
Client.listUser:listUser·p0.90        sample         10.404           ms/op
Client.listUser:listUser·p0.95        sample         11.190           ms/op
Client.listUser:listUser·p0.99        sample         14.662           ms/op
Client.listUser:listUser·p0.999       sample         18.092           ms/op
Client.listUser:listUser·p0.9999      sample         19.005           ms/op
Client.listUser:listUser·p1.00        sample         19.005           ms/op
