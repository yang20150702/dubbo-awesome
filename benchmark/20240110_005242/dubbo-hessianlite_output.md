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
# Warmup Iteration   1: 2.327 ops/ms
Iteration   1: 5.959 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.959 ops/ms


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
# Warmup Iteration   1: 5.654 ops/ms
Iteration   1: 13.629 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.629 ops/ms


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
# Warmup Iteration   1: 4.679 ops/ms
Iteration   1: 7.518 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.518 ops/ms


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
# Warmup Iteration   1: 2.221 ops/ms
Iteration   1: 3.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.810 ops/ms


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
# Warmup Iteration   1: 5.798 ±(99.9%) 0.088 ms/op
Iteration   1: 3.136 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.136 ms/op


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
# Warmup Iteration   1: 3.238 ±(99.9%) 0.028 ms/op
Iteration   1: 1.980 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.980 ms/op


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
# Warmup Iteration   1: 4.927 ±(99.9%) 0.052 ms/op
Iteration   1: 3.286 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.286 ms/op


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
# Warmup Iteration   1: 12.926 ±(99.9%) 0.246 ms/op
Iteration   1: 8.292 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.292 ms/op


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.117 ms/op
Iteration   1: 3.253 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.840 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   8.384 ms/op
                 createUser·p0.999:  13.189 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9825
  mean =      3.253 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1689 
    [ 2.500,  3.750) = 6921 
    [ 3.750,  5.000) = 800 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.840 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.384 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.076 ms/op
Iteration   1: 1.991 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.864 ms/op
                 existUser·p0.99:   3.289 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 18.316 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16095
  mean =      1.991 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 219 
    [ 1.250,  2.500) = 14091 
    [ 2.500,  3.750) = 1671 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.864 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     18.316 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.108 ms/op
Iteration   1: 2.904 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   2.748 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.676 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 8.518 ms/op
                 getUser·p1.00:   8.520 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11008
  mean =      2.904 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 6 
    [1.000, 1.500) = 60 
    [1.500, 2.000) = 449 
    [2.000, 2.500) = 3028 
    [2.500, 3.000) = 3479 
    [3.000, 3.500) = 2201 
    [3.500, 4.000) = 1091 
    [4.000, 4.500) = 384 
    [4.500, 5.000) = 81 
    [5.000, 5.500) = 96 
    [5.500, 6.000) = 47 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 41 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.676 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =      8.518 ms/op
     p(99.9990) =      8.520 ms/op
     p(99.9999) =      8.520 ms/op
    p(100.0000) =      8.520 ms/op


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
# Warmup Iteration   1: 14.159 ±(99.9%) 0.706 ms/op
Iteration   1: 8.266 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   8.086 ms/op
                 listUser·p0.90:   10.535 ms/op
                 listUser·p0.95:   11.583 ms/op
                 listUser·p0.99:   14.116 ms/op
                 listUser·p0.999:  17.725 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3868
  mean =      8.266 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 7 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 886 
    [ 7.500,  8.750) = 1131 
    [ 8.750, 10.000) = 819 
    [10.000, 11.250) = 328 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.601 ms/op
     p(50.0000) =      8.086 ms/op
     p(90.0000) =     10.535 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     14.116 ms/op
     p(99.9000) =     17.725 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.959          ops/ms
Client.existUser                       thrpt         13.629          ops/ms
Client.getUser                         thrpt          7.518          ops/ms
Client.listUser                        thrpt          3.810          ops/ms
Client.createUser                       avgt          3.136           ms/op
Client.existUser                        avgt          1.980           ms/op
Client.getUser                          avgt          3.286           ms/op
Client.listUser                         avgt          8.292           ms/op
Client.createUser                     sample   9825   3.253 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          0.645           ms/op
Client.createUser:createUser·p0.50    sample          3.133           ms/op
Client.createUser:createUser·p0.90    sample          3.840           ms/op
Client.createUser:createUser·p0.95    sample          4.751           ms/op
Client.createUser:createUser·p0.99    sample          8.384           ms/op
Client.createUser:createUser·p0.999   sample         13.189           ms/op
Client.createUser:createUser·p0.9999  sample         13.222           ms/op
Client.createUser:createUser·p1.00    sample         13.222           ms/op
Client.existUser                      sample  16095   1.991 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.483           ms/op
Client.existUser:existUser·p0.50      sample          1.845           ms/op
Client.existUser:existUser·p0.90      sample          2.552           ms/op
Client.existUser:existUser·p0.95      sample          2.864           ms/op
Client.existUser:existUser·p0.99      sample          3.289           ms/op
Client.existUser:existUser·p0.999     sample         17.695           ms/op
Client.existUser:existUser·p0.9999    sample         18.316           ms/op
Client.existUser:existUser·p1.00      sample         18.416           ms/op
Client.getUser                        sample  11008   2.904 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.523           ms/op
Client.getUser:getUser·p0.50          sample          2.748           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.125           ms/op
Client.getUser:getUser·p0.99          sample          5.676           ms/op
Client.getUser:getUser·p0.999         sample          8.438           ms/op
Client.getUser:getUser·p0.9999        sample          8.518           ms/op
Client.getUser:getUser·p1.00          sample          8.520           ms/op
Client.listUser                       sample   3868   8.266 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          2.601           ms/op
Client.listUser:listUser·p0.50        sample          8.086           ms/op
Client.listUser:listUser·p0.90        sample         10.535           ms/op
Client.listUser:listUser·p0.95        sample         11.583           ms/op
Client.listUser:listUser·p0.99        sample         14.116           ms/op
Client.listUser:listUser·p0.999       sample         17.725           ms/op
Client.listUser:listUser·p0.9999      sample         18.579           ms/op
Client.listUser:listUser·p1.00        sample         18.579           ms/op
