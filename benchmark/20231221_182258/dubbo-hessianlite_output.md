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
# Warmup Iteration   1: 2.423 ops/ms
Iteration   1: 6.367 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.367 ops/ms


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
# Warmup Iteration   1: 6.080 ops/ms
Iteration   1: 14.002 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.002 ops/ms


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
# Warmup Iteration   1: 4.490 ops/ms
Iteration   1: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.012 ops/ms


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
# Warmup Iteration   1: 2.575 ops/ms
Iteration   1: 3.507 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.507 ops/ms


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
# Warmup Iteration   1: 5.583 ±(99.9%) 0.065 ms/op
Iteration   1: 3.169 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.169 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.032 ms/op
Iteration   1: 1.726 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.726 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.054 ms/op
Iteration   1: 3.255 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.255 ms/op


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
# Warmup Iteration   1: 12.752 ±(99.9%) 0.279 ms/op
Iteration   1: 7.985 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.985 ms/op


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
# Warmup Iteration   1: 4.891 ±(99.9%) 0.101 ms/op
Iteration   1: 3.120 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  15.610 ms/op
                 createUser·p0.9999: 17.628 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10230
  mean =      3.120 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2839 
    [ 2.500,  3.750) = 5807 
    [ 3.750,  5.000) = 1390 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     15.610 ms/op
     p(99.9900) =     17.628 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.938 ±(99.9%) 0.081 ms/op
Iteration   1: 1.837 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.091 ms/op
                 existUser·p0.95:   2.269 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.457 ms/op
                 existUser·p0.9999: 9.323 ms/op
                 existUser·p1.00:   9.372 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17409
  mean =      1.837 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 32 
    [ 1.000,  2.000) = 14364 
    [ 2.000,  3.000) = 2770 
    [ 3.000,  4.000) = 150 
    [ 4.000,  5.000) = 76 
    [ 5.000,  6.000) = 2 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.091 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =      5.457 ms/op
     p(99.9900) =      9.323 ms/op
     p(99.9990) =      9.372 ms/op
     p(99.9999) =      9.372 ms/op
    p(100.0000) =      9.372 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.100 ms/op
Iteration   1: 2.771 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 20.339 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11536
  mean =      2.771 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5396 
    [ 2.500,  5.000) = 6006 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     20.339 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 11.027 ±(99.9%) 0.347 ms/op
Iteration   1: 7.581 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   7.225 ms/op
                 listUser·p0.90:   9.667 ms/op
                 listUser·p0.95:   11.010 ms/op
                 listUser·p0.99:   17.203 ms/op
                 listUser·p0.999:  22.284 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4225
  mean =      7.581 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 204 
    [ 5.000,  7.500) = 2213 
    [ 7.500, 10.000) = 1447 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.466 ms/op
     p(50.0000) =      7.225 ms/op
     p(90.0000) =      9.667 ms/op
     p(95.0000) =     11.010 ms/op
     p(99.0000) =     17.203 ms/op
     p(99.9000) =     22.284 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.367          ops/ms
Client.existUser                       thrpt         14.002          ops/ms
Client.getUser                         thrpt          9.012          ops/ms
Client.listUser                        thrpt          3.507          ops/ms
Client.createUser                       avgt          3.169           ms/op
Client.existUser                        avgt          1.726           ms/op
Client.getUser                          avgt          3.255           ms/op
Client.listUser                         avgt          7.985           ms/op
Client.createUser                     sample  10230   3.120 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.135           ms/op
Client.createUser:createUser·p0.50    sample          3.060           ms/op
Client.createUser:createUser·p0.90    sample          3.998           ms/op
Client.createUser:createUser·p0.95    sample          4.309           ms/op
Client.createUser:createUser·p0.99    sample          5.407           ms/op
Client.createUser:createUser·p0.999   sample         15.610           ms/op
Client.createUser:createUser·p0.9999  sample         17.628           ms/op
Client.createUser:createUser·p1.00    sample         17.629           ms/op
Client.existUser                      sample  17409   1.837 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.768           ms/op
Client.existUser:existUser·p0.50      sample          1.788           ms/op
Client.existUser:existUser·p0.90      sample          2.091           ms/op
Client.existUser:existUser·p0.95      sample          2.269           ms/op
Client.existUser:existUser·p0.99      sample          3.498           ms/op
Client.existUser:existUser·p0.999     sample          5.457           ms/op
Client.existUser:existUser·p0.9999    sample          9.323           ms/op
Client.existUser:existUser·p1.00      sample          9.372           ms/op
Client.getUser                        sample  11536   2.771 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.608           ms/op
Client.getUser:getUser·p0.50          sample          2.544           ms/op
Client.getUser:getUser·p0.90          sample          3.564           ms/op
Client.getUser:getUser·p0.95          sample          3.903           ms/op
Client.getUser:getUser·p0.99          sample          5.210           ms/op
Client.getUser:getUser·p0.999         sample         19.890           ms/op
Client.getUser:getUser·p0.9999        sample         20.339           ms/op
Client.getUser:getUser·p1.00          sample         20.349           ms/op
Client.listUser                       sample   4225   7.581 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.466           ms/op
Client.listUser:listUser·p0.50        sample          7.225           ms/op
Client.listUser:listUser·p0.90        sample          9.667           ms/op
Client.listUser:listUser·p0.95        sample         11.010           ms/op
Client.listUser:listUser·p0.99        sample         17.203           ms/op
Client.listUser:listUser·p0.999       sample         22.284           ms/op
Client.listUser:listUser·p0.9999      sample         25.264           ms/op
Client.listUser:listUser·p1.00        sample         25.264           ms/op
