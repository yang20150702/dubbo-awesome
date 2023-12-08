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
# Warmup Iteration   1: 2.358 ops/ms
Iteration   1: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.641 ops/ms


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
# Warmup Iteration   1: 5.616 ops/ms
Iteration   1: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.106 ops/ms


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
# Warmup Iteration   1: 4.586 ops/ms
Iteration   1: 8.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.944 ops/ms


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
# Warmup Iteration   1: 2.292 ops/ms
Iteration   1: 4.075 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.075 ops/ms


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.092 ms/op
Iteration   1: 3.116 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.116 ms/op


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.039 ms/op
Iteration   1: 2.051 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.051 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.056 ms/op
Iteration   1: 2.890 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.890 ms/op


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
# Warmup Iteration   1: 12.119 ±(99.9%) 0.234 ms/op
Iteration   1: 8.196 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.196 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.145 ms/op
Iteration   1: 3.017 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.732 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   7.887 ms/op
                 createUser·p0.999:  13.798 ms/op
                 createUser·p0.9999: 14.384 ms/op
                 createUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10854
  mean =      3.017 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2254 
    [ 2.500,  3.750) = 7469 
    [ 3.750,  5.000) = 838 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.887 ms/op
     p(99.9000) =     13.798 ms/op
     p(99.9900) =     14.384 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.066 ms/op
Iteration   1: 1.712 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.595 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   2.882 ms/op
                 existUser·p0.999:  4.567 ms/op
                 existUser·p0.9999: 7.240 ms/op
                 existUser·p1.00:   7.479 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18833
  mean =      1.712 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 60 
    [1.000, 1.500) = 6322 
    [1.500, 2.000) = 8671 
    [2.000, 2.500) = 3104 
    [2.500, 3.000) = 533 
    [3.000, 3.500) = 88 
    [3.500, 4.000) = 22 
    [4.000, 4.500) = 14 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.595 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      2.882 ms/op
     p(99.9000) =      4.567 ms/op
     p(99.9900) =      7.240 ms/op
     p(99.9990) =      7.479 ms/op
     p(99.9999) =      7.479 ms/op
    p(100.0000) =      7.479 ms/op


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
# Warmup Iteration   1: 4.561 ±(99.9%) 0.092 ms/op
Iteration   1: 3.166 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  17.161 ms/op
                 getUser·p0.9999: 24.731 ms/op
                 getUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10100
  mean =      3.166 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2024 
    [ 2.500,  5.000) = 7798 
    [ 5.000,  7.500) = 232 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     17.161 ms/op
     p(99.9900) =     24.731 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 12.461 ±(99.9%) 0.430 ms/op
Iteration   1: 10.190 ±(99.9%) 0.520 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   8.765 ms/op
                 listUser·p0.90:   13.025 ms/op
                 listUser·p0.95:   15.209 ms/op
                 listUser·p0.99:   64.700 ms/op
                 listUser·p0.999:  105.740 ms/op
                 listUser·p0.9999: 117.834 ms/op
                 listUser·p1.00:   117.834 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3133
  mean =     10.190 ±(99.9%) 0.520 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 2769 
    [ 12.500,  25.000) = 306 
    [ 25.000,  37.500) = 21 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 1 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 11 
    [ 87.500, 100.000) = 7 
    [100.000, 112.500) = 8 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      8.765 ms/op
     p(90.0000) =     13.025 ms/op
     p(95.0000) =     15.209 ms/op
     p(99.0000) =     64.700 ms/op
     p(99.9000) =    105.740 ms/op
     p(99.9900) =    117.834 ms/op
     p(99.9990) =    117.834 ms/op
     p(99.9999) =    117.834 ms/op
    p(100.0000) =    117.834 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.641          ops/ms
Client.existUser                       thrpt          13.106          ops/ms
Client.getUser                         thrpt           8.944          ops/ms
Client.listUser                        thrpt           4.075          ops/ms
Client.createUser                       avgt           3.116           ms/op
Client.existUser                        avgt           2.051           ms/op
Client.getUser                          avgt           2.890           ms/op
Client.listUser                         avgt           8.196           ms/op
Client.createUser                     sample  10854    3.017 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample           1.182           ms/op
Client.createUser:createUser·p0.50    sample           2.732           ms/op
Client.createUser:createUser·p0.90    sample           3.764           ms/op
Client.createUser:createUser·p0.95    sample           4.325           ms/op
Client.createUser:createUser·p0.99    sample           7.887           ms/op
Client.createUser:createUser·p0.999   sample          13.798           ms/op
Client.createUser:createUser·p0.9999  sample          14.384           ms/op
Client.createUser:createUser·p1.00    sample          14.385           ms/op
Client.existUser                      sample  18833    1.712 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample           0.583           ms/op
Client.existUser:existUser·p0.50      sample           1.595           ms/op
Client.existUser:existUser·p0.90      sample           2.257           ms/op
Client.existUser:existUser·p0.95      sample           2.421           ms/op
Client.existUser:existUser·p0.99      sample           2.882           ms/op
Client.existUser:existUser·p0.999     sample           4.567           ms/op
Client.existUser:existUser·p0.9999    sample           7.240           ms/op
Client.existUser:existUser·p1.00      sample           7.479           ms/op
Client.getUser                        sample  10100    3.166 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample           1.006           ms/op
Client.getUser:getUser·p0.50          sample           3.060           ms/op
Client.getUser:getUser·p0.90          sample           3.920           ms/op
Client.getUser:getUser·p0.95          sample           4.284           ms/op
Client.getUser:getUser·p0.99          sample           7.111           ms/op
Client.getUser:getUser·p0.999         sample          17.161           ms/op
Client.getUser:getUser·p0.9999        sample          24.731           ms/op
Client.getUser:getUser·p1.00          sample          24.740           ms/op
Client.listUser                       sample   3133   10.190 ± 0.520   ms/op
Client.listUser:listUser·p0.00        sample           1.595           ms/op
Client.listUser:listUser·p0.50        sample           8.765           ms/op
Client.listUser:listUser·p0.90        sample          13.025           ms/op
Client.listUser:listUser·p0.95        sample          15.209           ms/op
Client.listUser:listUser·p0.99        sample          64.700           ms/op
Client.listUser:listUser·p0.999       sample         105.740           ms/op
Client.listUser:listUser·p0.9999      sample         117.834           ms/op
Client.listUser:listUser·p1.00        sample         117.834           ms/op
