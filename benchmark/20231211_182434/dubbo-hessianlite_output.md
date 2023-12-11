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
# Warmup Iteration   1: 2.186 ops/ms
Iteration   1: 6.041 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.041 ops/ms


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
# Warmup Iteration   1: 6.301 ops/ms
Iteration   1: 13.677 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.677 ops/ms


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
# Warmup Iteration   1: 3.730 ops/ms
Iteration   1: 7.717 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.717 ops/ms


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
# Warmup Iteration   1: 2.085 ops/ms
Iteration   1: 3.378 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.378 ops/ms


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
# Warmup Iteration   1: 5.675 ±(99.9%) 0.075 ms/op
Iteration   1: 3.171 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.171 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.031 ms/op
Iteration   1: 1.796 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.796 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.059 ms/op
Iteration   1: 3.235 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.235 ms/op


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
# Warmup Iteration   1: 13.179 ±(99.9%) 0.221 ms/op
Iteration   1: 9.018 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.018 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.109 ms/op
Iteration   1: 3.055 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 12.838 ms/op
                 createUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10452
  mean =      3.055 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1767 
    [ 2.500,  3.750) = 7317 
    [ 3.750,  5.000) = 1215 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     12.838 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.109 ms/op
Iteration   1: 1.614 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   1.522 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.084 ms/op
                 existUser·p0.999:  4.784 ms/op
                 existUser·p0.9999: 5.911 ms/op
                 existUser·p1.00:   6.545 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19804
  mean =      1.614 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 434 
    [1.000, 1.500) = 8972 
    [1.500, 2.000) = 7273 
    [2.000, 2.500) = 2427 
    [2.500, 3.000) = 458 
    [3.000, 3.500) = 133 
    [3.500, 4.000) = 50 
    [4.000, 4.500) = 23 
    [4.500, 5.000) = 26 
    [5.000, 5.500) = 4 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.522 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.084 ms/op
     p(99.9000) =      4.784 ms/op
     p(99.9900) =      5.911 ms/op
     p(99.9990) =      6.545 ms/op
     p(99.9999) =      6.545 ms/op
    p(100.0000) =      6.545 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.133 ms/op
Iteration   1: 3.145 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.477 ms/op
                 getUser·p0.999:  12.873 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10146
  mean =      3.145 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1708 
    [ 2.500,  3.750) = 6708 
    [ 3.750,  5.000) = 1537 
    [ 5.000,  6.250) = 131 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.477 ms/op
     p(99.9000) =     12.873 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 13.970 ±(99.9%) 0.434 ms/op
Iteration   1: 9.560 ±(99.9%) 0.143 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   9.249 ms/op
                 listUser·p0.90:   12.568 ms/op
                 listUser·p0.95:   14.296 ms/op
                 listUser·p0.99:   17.089 ms/op
                 listUser·p0.999:  23.479 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3348
  mean =      9.560 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 44 
    [ 5.000,  7.500) = 603 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 940 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      9.249 ms/op
     p(90.0000) =     12.568 ms/op
     p(95.0000) =     14.296 ms/op
     p(99.0000) =     17.089 ms/op
     p(99.9000) =     23.479 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.041          ops/ms
Client.existUser                       thrpt         13.677          ops/ms
Client.getUser                         thrpt          7.717          ops/ms
Client.listUser                        thrpt          3.378          ops/ms
Client.createUser                       avgt          3.171           ms/op
Client.existUser                        avgt          1.796           ms/op
Client.getUser                          avgt          3.235           ms/op
Client.listUser                         avgt          9.018           ms/op
Client.createUser                     sample  10452   3.055 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          1.037           ms/op
Client.createUser:createUser·p0.50    sample          2.900           ms/op
Client.createUser:createUser·p0.90    sample          4.018           ms/op
Client.createUser:createUser·p0.95    sample          4.432           ms/op
Client.createUser:createUser·p0.99    sample          5.276           ms/op
Client.createUser:createUser·p0.999   sample         10.289           ms/op
Client.createUser:createUser·p0.9999  sample         12.838           ms/op
Client.createUser:createUser·p1.00    sample         12.845           ms/op
Client.existUser                      sample  19804   1.614 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.681           ms/op
Client.existUser:existUser·p0.50      sample          1.522           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.351           ms/op
Client.existUser:existUser·p0.99      sample          3.084           ms/op
Client.existUser:existUser·p0.999     sample          4.784           ms/op
Client.existUser:existUser·p0.9999    sample          5.911           ms/op
Client.existUser:existUser·p1.00      sample          6.545           ms/op
Client.getUser                        sample  10146   3.145 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          1.096           ms/op
Client.getUser:getUser·p0.50          sample          2.994           ms/op
Client.getUser:getUser·p0.90          sample          3.977           ms/op
Client.getUser:getUser·p0.95          sample          4.284           ms/op
Client.getUser:getUser·p0.99          sample          5.477           ms/op
Client.getUser:getUser·p0.999         sample         12.873           ms/op
Client.getUser:getUser·p0.9999        sample         15.041           ms/op
Client.getUser:getUser·p1.00          sample         15.041           ms/op
Client.listUser                       sample   3348   9.560 ± 0.143   ms/op
Client.listUser:listUser·p0.00        sample          1.915           ms/op
Client.listUser:listUser·p0.50        sample          9.249           ms/op
Client.listUser:listUser·p0.90        sample         12.568           ms/op
Client.listUser:listUser·p0.95        sample         14.296           ms/op
Client.listUser:listUser·p0.99        sample         17.089           ms/op
Client.listUser:listUser·p0.999       sample         23.479           ms/op
Client.listUser:listUser·p0.9999      sample         25.854           ms/op
Client.listUser:listUser·p1.00        sample         25.854           ms/op
