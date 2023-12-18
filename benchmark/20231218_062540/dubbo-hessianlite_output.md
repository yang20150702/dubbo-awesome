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
# Warmup Iteration   1: 2.393 ops/ms
Iteration   1: 5.974 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.974 ops/ms


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
# Warmup Iteration   1: 6.345 ops/ms
Iteration   1: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.706 ops/ms


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
# Warmup Iteration   1: 4.033 ops/ms
Iteration   1: 9.266 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.266 ops/ms


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
# Warmup Iteration   1: 1.877 ops/ms
Iteration   1: 3.187 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.187 ops/ms


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
# Warmup Iteration   1: 6.165 ±(99.9%) 0.091 ms/op
Iteration   1: 3.071 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.071 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.073 ms/op
Iteration   1: 1.900 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.057 ms/op
Iteration   1: 3.176 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.176 ms/op


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
# Warmup Iteration   1: 12.828 ±(99.9%) 0.246 ms/op
Iteration   1: 9.010 ±(99.9%) 0.125 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.010 ms/op


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.100 ms/op
Iteration   1: 3.345 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   8.393 ms/op
                 createUser·p0.999:  17.648 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9572
  mean =      3.345 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1469 
    [ 2.500,  5.000) = 7765 
    [ 5.000,  7.500) = 221 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      8.393 ms/op
     p(99.9000) =     17.648 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 2.948 ±(99.9%) 0.061 ms/op
Iteration   1: 1.894 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.356 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   3.101 ms/op
                 existUser·p0.999:  22.544 ms/op
                 existUser·p0.9999: 23.136 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16930
  mean =      1.894 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16062 
    [ 2.500,  5.000) = 823 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     23.136 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.095 ms/op
Iteration   1: 3.229 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.497 ms/op
                 getUser·p0.999:  8.012 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9898
  mean =      3.229 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 2009 
    [ 2.500,  3.750) = 5799 
    [ 3.750,  5.000) = 1870 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.497 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 12.474 ±(99.9%) 0.401 ms/op
Iteration   1: 7.910 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   7.397 ms/op
                 listUser·p0.90:   10.142 ms/op
                 listUser·p0.95:   11.404 ms/op
                 listUser·p0.99:   20.480 ms/op
                 listUser·p0.999:  31.905 ms/op
                 listUser·p0.9999: 35.914 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4038
  mean =      7.910 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 104 
    [ 5.000,  7.500) = 2028 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      7.397 ms/op
     p(90.0000) =     10.142 ms/op
     p(95.0000) =     11.404 ms/op
     p(99.0000) =     20.480 ms/op
     p(99.9000) =     31.905 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.974          ops/ms
Client.existUser                       thrpt         12.706          ops/ms
Client.getUser                         thrpt          9.266          ops/ms
Client.listUser                        thrpt          3.187          ops/ms
Client.createUser                       avgt          3.071           ms/op
Client.existUser                        avgt          1.900           ms/op
Client.getUser                          avgt          3.176           ms/op
Client.listUser                         avgt          9.010           ms/op
Client.createUser                     sample   9572   3.345 ± 0.046   ms/op
Client.createUser:createUser·p0.00    sample          0.725           ms/op
Client.createUser:createUser·p0.50    sample          3.166           ms/op
Client.createUser:createUser·p0.90    sample          4.170           ms/op
Client.createUser:createUser·p0.95    sample          4.628           ms/op
Client.createUser:createUser·p0.99    sample          8.393           ms/op
Client.createUser:createUser·p0.999   sample         17.648           ms/op
Client.createUser:createUser·p0.9999  sample         21.266           ms/op
Client.createUser:createUser·p1.00    sample         21.266           ms/op
Client.existUser                      sample  16930   1.894 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.356           ms/op
Client.existUser:existUser·p0.50      sample          1.808           ms/op
Client.existUser:existUser·p0.90      sample          2.335           ms/op
Client.existUser:existUser·p0.95      sample          2.503           ms/op
Client.existUser:existUser·p0.99      sample          3.101           ms/op
Client.existUser:existUser·p0.999     sample         22.544           ms/op
Client.existUser:existUser·p0.9999    sample         23.136           ms/op
Client.existUser:existUser·p1.00      sample         23.364           ms/op
Client.getUser                        sample   9898   3.229 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.754           ms/op
Client.getUser:getUser·p0.50          sample          3.232           ms/op
Client.getUser:getUser·p0.90          sample          4.076           ms/op
Client.getUser:getUser·p0.95          sample          4.358           ms/op
Client.getUser:getUser·p0.99          sample          6.497           ms/op
Client.getUser:getUser·p0.999         sample          8.012           ms/op
Client.getUser:getUser·p0.9999        sample         12.894           ms/op
Client.getUser:getUser·p1.00          sample         12.894           ms/op
Client.listUser                       sample   4038   7.910 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          1.907           ms/op
Client.listUser:listUser·p0.50        sample          7.397           ms/op
Client.listUser:listUser·p0.90        sample         10.142           ms/op
Client.listUser:listUser·p0.95        sample         11.404           ms/op
Client.listUser:listUser·p0.99        sample         20.480           ms/op
Client.listUser:listUser·p0.999       sample         31.905           ms/op
Client.listUser:listUser·p0.9999      sample         35.914           ms/op
Client.listUser:listUser·p1.00        sample         35.914           ms/op
