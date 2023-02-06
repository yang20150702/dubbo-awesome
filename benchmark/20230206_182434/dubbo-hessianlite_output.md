# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.164 ops/ms
Iteration   1: 2.980 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.980 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ops/ms
Iteration   1: 7.148 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.148 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.099 ops/ms
Iteration   1: 4.915 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.915 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.943 ops/ms
Iteration   1: 1.385 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.385 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 13.365 ±(99.9%) 0.150 ms/op
Iteration   1: 6.599 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.599 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.082 ms/op
Iteration   1: 3.820 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.820 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.158 ±(99.9%) 0.110 ms/op
Iteration   1: 5.015 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.275 ±(99.9%) 0.411 ms/op
Iteration   1: 16.290 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.541 ±(99.9%) 0.274 ms/op
Iteration   1: 6.441 ±(99.9%) 0.143 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.775 ms/op
                 createUser·p0.90:   8.448 ms/op
                 createUser·p0.95:   12.534 ms/op
                 createUser·p0.99:   16.941 ms/op
                 createUser·p0.999:  30.115 ms/op
                 createUser·p0.9999: 36.504 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4971
  mean =      6.441 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 690 
    [ 5.000,  7.500) = 3761 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.216 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      8.448 ms/op
     p(95.0000) =     12.534 ms/op
     p(99.0000) =     16.941 ms/op
     p(99.9000) =     30.115 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.449 ±(99.9%) 0.220 ms/op
Iteration   1: 3.406 ±(99.9%) 0.074 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   7.216 ms/op
                 existUser·p0.99:   13.303 ms/op
                 existUser·p0.999:  21.436 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9401
  mean =      3.406 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1963 
    [ 2.500,  5.000) = 6614 
    [ 5.000,  7.500) = 359 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      7.216 ms/op
     p(99.0000) =     13.303 ms/op
     p(99.9000) =     21.436 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ±(99.9%) 0.279 ms/op
Iteration   1: 4.299 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  14.684 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7442
  mean =      4.299 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 6320 
    [ 5.000,  7.500) = 814 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     14.684 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.715 ±(99.9%) 0.889 ms/op
Iteration   1: 16.296 ±(99.9%) 0.209 ms/op
                 listUser·p0.00:   5.259 ms/op
                 listUser·p0.50:   15.991 ms/op
                 listUser·p0.90:   18.088 ms/op
                 listUser·p0.95:   20.283 ms/op
                 listUser·p0.99:   29.709 ms/op
                 listUser·p0.999:  32.604 ms/op
                 listUser·p0.9999: 33.751 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1971
  mean =     16.296 ±(99.9%) 0.209 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 536 
    [15.000, 17.500) = 1040 
    [17.500, 20.000) = 237 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.259 ms/op
     p(50.0000) =     15.991 ms/op
     p(90.0000) =     18.088 ms/op
     p(95.0000) =     20.283 ms/op
     p(99.0000) =     29.709 ms/op
     p(99.9000) =     32.604 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.980          ops/ms
Client.existUser                       thrpt         7.148          ops/ms
Client.getUser                         thrpt         4.915          ops/ms
Client.listUser                        thrpt         1.385          ops/ms
Client.createUser                       avgt         6.599           ms/op
Client.existUser                        avgt         3.820           ms/op
Client.getUser                          avgt         5.015           ms/op
Client.listUser                         avgt        16.290           ms/op
Client.createUser                     sample  4971   6.441 ± 0.143   ms/op
Client.createUser:createUser·p0.00    sample         2.216           ms/op
Client.createUser:createUser·p0.50    sample         5.775           ms/op
Client.createUser:createUser·p0.90    sample         8.448           ms/op
Client.createUser:createUser·p0.95    sample        12.534           ms/op
Client.createUser:createUser·p0.99    sample        16.941           ms/op
Client.createUser:createUser·p0.999   sample        30.115           ms/op
Client.createUser:createUser·p0.9999  sample        36.504           ms/op
Client.createUser:createUser·p1.00    sample        36.504           ms/op
Client.existUser                      sample  9401   3.406 ± 0.074   ms/op
Client.existUser:existUser·p0.00      sample         0.539           ms/op
Client.existUser:existUser·p0.50      sample         2.949           ms/op
Client.existUser:existUser·p0.90      sample         4.334           ms/op
Client.existUser:existUser·p0.95      sample         7.216           ms/op
Client.existUser:existUser·p0.99      sample        13.303           ms/op
Client.existUser:existUser·p0.999     sample        21.436           ms/op
Client.existUser:existUser·p0.9999    sample        27.394           ms/op
Client.existUser:existUser·p1.00      sample        27.394           ms/op
Client.getUser                        sample  7442   4.299 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample         1.249           ms/op
Client.getUser:getUser·p0.50          sample         4.096           ms/op
Client.getUser:getUser·p0.90          sample         5.161           ms/op
Client.getUser:getUser·p0.95          sample         6.390           ms/op
Client.getUser:getUser·p0.99          sample        10.781           ms/op
Client.getUser:getUser·p0.999         sample        14.684           ms/op
Client.getUser:getUser·p0.9999        sample        21.791           ms/op
Client.getUser:getUser·p1.00          sample        21.791           ms/op
Client.listUser                       sample  1971  16.296 ± 0.209   ms/op
Client.listUser:listUser·p0.00        sample         5.259           ms/op
Client.listUser:listUser·p0.50        sample        15.991           ms/op
Client.listUser:listUser·p0.90        sample        18.088           ms/op
Client.listUser:listUser·p0.95        sample        20.283           ms/op
Client.listUser:listUser·p0.99        sample        29.709           ms/op
Client.listUser:listUser·p0.999       sample        32.604           ms/op
Client.listUser:listUser·p0.9999      sample        33.751           ms/op
Client.listUser:listUser·p1.00        sample        33.751           ms/op
