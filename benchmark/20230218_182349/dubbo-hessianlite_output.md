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
# Warmup Iteration   1: 1.152 ops/ms
Iteration   1: 2.713 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.713 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.787 ops/ms
Iteration   1: 6.131 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.131 ops/ms


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
# Warmup Iteration   1: 1.930 ops/ms
Iteration   1: 3.789 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.789 ops/ms


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
# Warmup Iteration   1: 0.850 ops/ms
Iteration   1: 1.197 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.197 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 16.554 ±(99.9%) 0.240 ms/op
Iteration   1: 7.317 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.317 ms/op


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
# Warmup Iteration   1: 7.476 ±(99.9%) 0.088 ms/op
Iteration   1: 3.662 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.662 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.219 ±(99.9%) 0.147 ms/op
Iteration   1: 4.955 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.955 ms/op


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
# Warmup Iteration   1: 25.063 ±(99.9%) 0.394 ms/op
Iteration   1: 16.915 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.915 ms/op


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
# Warmup Iteration   1: 14.755 ±(99.9%) 0.549 ms/op
Iteration   1: 7.141 ±(99.9%) 0.125 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   7.119 ms/op
                 createUser·p0.90:   8.192 ms/op
                 createUser·p0.95:   11.289 ms/op
                 createUser·p0.99:   22.741 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4479
  mean =      7.141 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 218 
    [ 5.000,  7.500) = 2992 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      7.119 ms/op
     p(90.0000) =      8.192 ms/op
     p(95.0000) =     11.289 ms/op
     p(99.0000) =     22.741 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.954 ±(99.9%) 0.281 ms/op
Iteration   1: 4.234 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   12.501 ms/op
                 existUser·p0.999:  18.165 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7649
  mean =      4.234 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 144 
    [ 2.500,  3.750) = 2165 
    [ 3.750,  5.000) = 4863 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =     12.501 ms/op
     p(99.9000) =     18.165 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 7.975 ±(99.9%) 0.284 ms/op
Iteration   1: 4.746 ±(99.9%) 0.086 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   14.319 ms/op
                 getUser·p0.999:  26.944 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6740
  mean =      4.746 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 4840 
    [ 5.000,  7.500) = 1537 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =     14.319 ms/op
     p(99.9000) =     26.944 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 24.512 ±(99.9%) 0.710 ms/op
Iteration   1: 18.740 ±(99.9%) 0.431 ms/op
                 listUser·p0.00:   8.102 ms/op
                 listUser·p0.50:   17.351 ms/op
                 listUser·p0.90:   26.054 ms/op
                 listUser·p0.95:   31.228 ms/op
                 listUser·p0.99:   40.086 ms/op
                 listUser·p0.999:  44.468 ms/op
                 listUser·p0.9999: 44.564 ms/op
                 listUser·p1.00:   44.564 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1732
  mean =     18.740 ±(99.9%) 0.431 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 12 
    [10.000, 15.000) = 247 
    [15.000, 20.000) = 1174 
    [20.000, 25.000) = 104 
    [25.000, 30.000) = 90 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      8.102 ms/op
     p(50.0000) =     17.351 ms/op
     p(90.0000) =     26.054 ms/op
     p(95.0000) =     31.228 ms/op
     p(99.0000) =     40.086 ms/op
     p(99.9000) =     44.468 ms/op
     p(99.9900) =     44.564 ms/op
     p(99.9990) =     44.564 ms/op
     p(99.9999) =     44.564 ms/op
    p(100.0000) =     44.564 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.713          ops/ms
Client.existUser                       thrpt         6.131          ops/ms
Client.getUser                         thrpt         3.789          ops/ms
Client.listUser                        thrpt         1.197          ops/ms
Client.createUser                       avgt         7.317           ms/op
Client.existUser                        avgt         3.662           ms/op
Client.getUser                          avgt         4.955           ms/op
Client.listUser                         avgt        16.915           ms/op
Client.createUser                     sample  4479   7.141 ± 0.125   ms/op
Client.createUser:createUser·p0.00    sample         2.228           ms/op
Client.createUser:createUser·p0.50    sample         7.119           ms/op
Client.createUser:createUser·p0.90    sample         8.192           ms/op
Client.createUser:createUser·p0.95    sample        11.289           ms/op
Client.createUser:createUser·p0.99    sample        22.741           ms/op
Client.createUser:createUser·p0.999   sample        24.347           ms/op
Client.createUser:createUser·p0.9999  sample        28.901           ms/op
Client.createUser:createUser·p1.00    sample        28.901           ms/op
Client.existUser                      sample  7649   4.234 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         1.128           ms/op
Client.existUser:existUser·p0.50      sample         4.116           ms/op
Client.existUser:existUser·p0.90      sample         4.628           ms/op
Client.existUser:existUser·p0.95      sample         5.890           ms/op
Client.existUser:existUser·p0.99      sample        12.501           ms/op
Client.existUser:existUser·p0.999     sample        18.165           ms/op
Client.existUser:existUser·p0.9999    sample        18.612           ms/op
Client.existUser:existUser·p1.00      sample        18.612           ms/op
Client.getUser                        sample  6740   4.746 ± 0.086   ms/op
Client.getUser:getUser·p0.00          sample         1.253           ms/op
Client.getUser:getUser·p0.50          sample         4.334           ms/op
Client.getUser:getUser·p0.90          sample         6.038           ms/op
Client.getUser:getUser·p0.95          sample         6.783           ms/op
Client.getUser:getUser·p0.99          sample        14.319           ms/op
Client.getUser:getUser·p0.999         sample        26.944           ms/op
Client.getUser:getUser·p0.9999        sample        28.115           ms/op
Client.getUser:getUser·p1.00          sample        28.115           ms/op
Client.listUser                       sample  1732  18.740 ± 0.431   ms/op
Client.listUser:listUser·p0.00        sample         8.102           ms/op
Client.listUser:listUser·p0.50        sample        17.351           ms/op
Client.listUser:listUser·p0.90        sample        26.054           ms/op
Client.listUser:listUser·p0.95        sample        31.228           ms/op
Client.listUser:listUser·p0.99        sample        40.086           ms/op
Client.listUser:listUser·p0.999       sample        44.468           ms/op
Client.listUser:listUser·p0.9999      sample        44.564           ms/op
Client.listUser:listUser·p1.00        sample        44.564           ms/op
