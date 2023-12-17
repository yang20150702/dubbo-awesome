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
# Warmup Iteration   1: 2.448 ops/ms
Iteration   1: 6.948 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.948 ops/ms


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
# Warmup Iteration   1: 6.222 ops/ms
Iteration   1: 13.111 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.111 ops/ms


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
# Warmup Iteration   1: 4.184 ops/ms
Iteration   1: 7.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.377 ops/ms


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
# Warmup Iteration   1: 2.355 ops/ms
Iteration   1: 3.781 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.781 ops/ms


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
# Warmup Iteration   1: 5.843 ±(99.9%) 0.093 ms/op
Iteration   1: 3.262 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.262 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.066 ms/op
Iteration   1: 1.920 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.920 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.053 ms/op
Iteration   1: 2.735 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.735 ms/op


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
# Warmup Iteration   1: 14.141 ±(99.9%) 0.275 ms/op
Iteration   1: 8.601 ±(99.9%) 0.143 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.601 ms/op


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
# Warmup Iteration   1: 5.317 ±(99.9%) 0.137 ms/op
Iteration   1: 3.410 ±(99.9%) 0.135 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   8.459 ms/op
                 createUser·p0.999:  71.798 ms/op
                 createUser·p0.9999: 85.590 ms/op
                 createUser·p1.00:   85.590 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9370
  mean =      3.410 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9060 
    [ 5.000, 10.000) = 224 
    [10.000, 15.000) = 36 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 5 
    [70.000, 75.000) = 6 
    [75.000, 80.000) = 4 
    [80.000, 85.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      8.459 ms/op
     p(99.9000) =     71.798 ms/op
     p(99.9900) =     85.590 ms/op
     p(99.9990) =     85.590 ms/op
     p(99.9999) =     85.590 ms/op
    p(100.0000) =     85.590 ms/op


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
# Warmup Iteration   1: 2.921 ±(99.9%) 0.065 ms/op
Iteration   1: 1.990 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.699 ms/op
                 existUser·p0.95:   2.970 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  13.461 ms/op
                 existUser·p0.9999: 14.512 ms/op
                 existUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16066
  mean =      1.990 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 417 
    [ 1.250,  2.500) = 13125 
    [ 2.500,  3.750) = 2366 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =     13.461 ms/op
     p(99.9900) =     14.512 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.094 ms/op
Iteration   1: 2.696 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.321 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 7.251 ms/op
                 getUser·p1.00:   7.266 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11857
  mean =      2.696 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 370 
    [2.000, 2.500) = 5218 
    [2.500, 3.000) = 3265 
    [3.000, 3.500) = 1990 
    [3.500, 4.000) = 674 
    [4.000, 4.500) = 225 
    [4.500, 5.000) = 45 
    [5.000, 5.500) = 7 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 29 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.321 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =      7.251 ms/op
     p(99.9990) =      7.266 ms/op
     p(99.9999) =      7.266 ms/op
    p(100.0000) =      7.266 ms/op


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
# Warmup Iteration   1: 12.208 ±(99.9%) 0.395 ms/op
Iteration   1: 7.838 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   7.332 ms/op
                 listUser·p0.90:   10.564 ms/op
                 listUser·p0.95:   11.878 ms/op
                 listUser·p0.99:   16.667 ms/op
                 listUser·p0.999:  22.378 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4081
  mean =      7.838 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 180 
    [ 5.000,  7.500) = 2020 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      7.332 ms/op
     p(90.0000) =     10.564 ms/op
     p(95.0000) =     11.878 ms/op
     p(99.0000) =     16.667 ms/op
     p(99.9000) =     22.378 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.948          ops/ms
Client.existUser                       thrpt         13.111          ops/ms
Client.getUser                         thrpt          7.377          ops/ms
Client.listUser                        thrpt          3.781          ops/ms
Client.createUser                       avgt          3.262           ms/op
Client.existUser                        avgt          1.920           ms/op
Client.getUser                          avgt          2.735           ms/op
Client.listUser                         avgt          8.601           ms/op
Client.createUser                     sample   9370   3.410 ± 0.135   ms/op
Client.createUser:createUser·p0.00    sample          1.178           ms/op
Client.createUser:createUser·p0.50    sample          3.043           ms/op
Client.createUser:createUser·p0.90    sample          3.854           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample          8.459           ms/op
Client.createUser:createUser·p0.999   sample         71.798           ms/op
Client.createUser:createUser·p0.9999  sample         85.590           ms/op
Client.createUser:createUser·p1.00    sample         85.590           ms/op
Client.existUser                      sample  16066   1.990 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.515           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.699           ms/op
Client.existUser:existUser·p0.95      sample          2.970           ms/op
Client.existUser:existUser·p0.99      sample          3.711           ms/op
Client.existUser:existUser·p0.999     sample         13.461           ms/op
Client.existUser:existUser·p0.9999    sample         14.512           ms/op
Client.existUser:existUser·p1.00      sample         14.582           ms/op
Client.getUser                        sample  11857   2.696 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          0.849           ms/op
Client.getUser:getUser·p0.50          sample          2.531           ms/op
Client.getUser:getUser·p0.90          sample          3.416           ms/op
Client.getUser:getUser·p0.95          sample          3.727           ms/op
Client.getUser:getUser·p0.99          sample          4.321           ms/op
Client.getUser:getUser·p0.999         sample          6.652           ms/op
Client.getUser:getUser·p0.9999        sample          7.251           ms/op
Client.getUser:getUser·p1.00          sample          7.266           ms/op
Client.listUser                       sample   4081   7.838 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          1.745           ms/op
Client.listUser:listUser·p0.50        sample          7.332           ms/op
Client.listUser:listUser·p0.90        sample         10.564           ms/op
Client.listUser:listUser·p0.95        sample         11.878           ms/op
Client.listUser:listUser·p0.99        sample         16.667           ms/op
Client.listUser:listUser·p0.999       sample         22.378           ms/op
Client.listUser:listUser·p0.9999      sample         23.790           ms/op
Client.listUser:listUser·p1.00        sample         23.790           ms/op
