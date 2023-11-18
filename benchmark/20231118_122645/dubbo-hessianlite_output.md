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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 5.573 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.573 ops/ms


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
# Warmup Iteration   1: 5.830 ops/ms
Iteration   1: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.675 ops/ms


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
# Warmup Iteration   1: 4.062 ops/ms
Iteration   1: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.358 ops/ms


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
# Warmup Iteration   1: 2.192 ops/ms
Iteration   1: 3.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.387 ops/ms


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
# Warmup Iteration   1: 5.243 ±(99.9%) 0.075 ms/op
Iteration   1: 3.171 ±(99.9%) 0.026 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ±(99.9%) 0.025 ms/op
Iteration   1: 1.806 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.806 ms/op


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.042 ms/op
Iteration   1: 2.940 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.940 ms/op


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
# Warmup Iteration   1: 12.967 ±(99.9%) 0.320 ms/op
Iteration   1: 8.383 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.383 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.100 ms/op
Iteration   1: 2.818 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  14.172 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11334
  mean =      2.818 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3658 
    [ 2.500,  3.750) = 7174 
    [ 3.750,  5.000) = 401 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.089 ms/op
Iteration   1: 2.142 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.647 ms/op
                 existUser·p0.95:   2.997 ms/op
                 existUser·p0.99:   7.791 ms/op
                 existUser·p0.999:  28.767 ms/op
                 existUser·p0.9999: 29.421 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15106
  mean =      2.142 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12891 
    [ 2.500,  5.000) = 1921 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.647 ms/op
     p(95.0000) =      2.997 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     28.767 ms/op
     p(99.9900) =     29.421 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.174 ms/op
Iteration   1: 2.732 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.658 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  12.878 ms/op
                 getUser·p0.9999: 13.289 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11807
  mean =      2.732 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 4903 
    [ 2.500,  3.750) = 6357 
    [ 3.750,  5.000) = 468 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     13.289 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 11.810 ±(99.9%) 0.377 ms/op
Iteration   1: 8.454 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   7.987 ms/op
                 listUser·p0.90:   11.518 ms/op
                 listUser·p0.95:   12.993 ms/op
                 listUser·p0.99:   17.174 ms/op
                 listUser·p0.999:  26.257 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3789
  mean =      8.454 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 132 
    [ 5.000,  7.500) = 1302 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      7.987 ms/op
     p(90.0000) =     11.518 ms/op
     p(95.0000) =     12.993 ms/op
     p(99.0000) =     17.174 ms/op
     p(99.9000) =     26.257 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.573          ops/ms
Client.existUser                       thrpt         12.675          ops/ms
Client.getUser                         thrpt          8.358          ops/ms
Client.listUser                        thrpt          3.387          ops/ms
Client.createUser                       avgt          3.171           ms/op
Client.existUser                        avgt          1.806           ms/op
Client.getUser                          avgt          2.940           ms/op
Client.listUser                         avgt          8.383           ms/op
Client.createUser                     sample  11334   2.818 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.425           ms/op
Client.createUser:createUser·p0.50    sample          2.621           ms/op
Client.createUser:createUser·p0.90    sample          3.371           ms/op
Client.createUser:createUser·p0.95    sample          3.682           ms/op
Client.createUser:createUser·p0.99    sample          4.907           ms/op
Client.createUser:createUser·p0.999   sample         14.172           ms/op
Client.createUser:createUser·p0.9999  sample         14.238           ms/op
Client.createUser:createUser·p1.00    sample         14.238           ms/op
Client.existUser                      sample  15106   2.142 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample          0.517           ms/op
Client.existUser:existUser·p0.50      sample          1.966           ms/op
Client.existUser:existUser·p0.90      sample          2.647           ms/op
Client.existUser:existUser·p0.95      sample          2.997           ms/op
Client.existUser:existUser·p0.99      sample          7.791           ms/op
Client.existUser:existUser·p0.999     sample         28.767           ms/op
Client.existUser:existUser·p0.9999    sample         29.421           ms/op
Client.existUser:existUser·p1.00      sample         29.655           ms/op
Client.getUser                        sample  11807   2.732 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.989           ms/op
Client.getUser:getUser·p0.50          sample          2.658           ms/op
Client.getUser:getUser·p0.90          sample          3.437           ms/op
Client.getUser:getUser·p0.95          sample          3.719           ms/op
Client.getUser:getUser·p0.99          sample          4.604           ms/op
Client.getUser:getUser·p0.999         sample         12.878           ms/op
Client.getUser:getUser·p0.9999        sample         13.289           ms/op
Client.getUser:getUser·p1.00          sample         13.337           ms/op
Client.listUser                       sample   3789   8.454 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          1.548           ms/op
Client.listUser:listUser·p0.50        sample          7.987           ms/op
Client.listUser:listUser·p0.90        sample         11.518           ms/op
Client.listUser:listUser·p0.95        sample         12.993           ms/op
Client.listUser:listUser·p0.99        sample         17.174           ms/op
Client.listUser:listUser·p0.999       sample         26.257           ms/op
Client.listUser:listUser·p0.9999      sample         28.082           ms/op
Client.listUser:listUser·p1.00        sample         28.082           ms/op
