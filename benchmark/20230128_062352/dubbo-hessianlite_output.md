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
# Warmup Iteration   1: 0.881 ops/ms
Iteration   1: 2.342 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.342 ops/ms


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
# Warmup Iteration   1: 2.348 ops/ms
Iteration   1: 7.391 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.391 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.020 ops/ms
Iteration   1: 4.943 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.943 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.817 ops/ms
Iteration   1: 1.266 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.266 ops/ms


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
# Warmup Iteration   1: 20.476 ±(99.9%) 0.249 ms/op
Iteration   1: 7.455 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.455 ms/op


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
# Warmup Iteration   1: 7.675 ±(99.9%) 0.089 ms/op
Iteration   1: 3.530 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.530 ms/op


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
# Warmup Iteration   1: 11.726 ±(99.9%) 0.144 ms/op
Iteration   1: 4.993 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.993 ms/op


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
# Warmup Iteration   1: 29.997 ±(99.9%) 0.538 ms/op
Iteration   1: 19.274 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.274 ms/op


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
# Warmup Iteration   1: 13.781 ±(99.9%) 0.462 ms/op
Iteration   1: 7.821 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   7.578 ms/op
                 createUser·p0.90:   8.503 ms/op
                 createUser·p0.95:   9.961 ms/op
                 createUser·p0.99:   20.054 ms/op
                 createUser·p0.999:  23.488 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4099
  mean =      7.821 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 112 
    [ 5.000,  7.500) = 1603 
    [ 7.500, 10.000) = 2146 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      7.578 ms/op
     p(90.0000) =      8.503 ms/op
     p(95.0000) =      9.961 ms/op
     p(99.0000) =     20.054 ms/op
     p(99.9000) =     23.488 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 8.647 ±(99.9%) 0.278 ms/op
Iteration   1: 4.977 ±(99.9%) 0.106 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.094 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   14.287 ms/op
                 existUser·p0.999:  39.002 ms/op
                 existUser·p0.9999: 39.191 ms/op
                 existUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6441
  mean =      4.977 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 5494 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.094 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =     14.287 ms/op
     p(99.9000) =     39.002 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 11.071 ±(99.9%) 0.409 ms/op
Iteration   1: 5.335 ±(99.9%) 0.098 ms/op
                 getUser·p0.00:   2.351 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   7.246 ms/op
                 getUser·p0.99:   17.200 ms/op
                 getUser·p0.999:  24.281 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6061
  mean =      5.335 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 3287 
    [ 5.000,  7.500) = 2472 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.351 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      7.246 ms/op
     p(99.0000) =     17.200 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 28.483 ±(99.9%) 1.139 ms/op
Iteration   1: 18.224 ±(99.9%) 0.239 ms/op
                 listUser·p0.00:   8.962 ms/op
                 listUser·p0.50:   18.514 ms/op
                 listUser·p0.90:   21.332 ms/op
                 listUser·p0.95:   22.744 ms/op
                 listUser·p0.99:   29.184 ms/op
                 listUser·p0.999:  35.538 ms/op
                 listUser·p0.9999: 35.586 ms/op
                 listUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1738
  mean =     18.224 ±(99.9%) 0.239 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 564 
    [17.500, 20.000) = 770 
    [20.000, 22.500) = 198 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      8.962 ms/op
     p(50.0000) =     18.514 ms/op
     p(90.0000) =     21.332 ms/op
     p(95.0000) =     22.744 ms/op
     p(99.0000) =     29.184 ms/op
     p(99.9000) =     35.538 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.342          ops/ms
Client.existUser                       thrpt         7.391          ops/ms
Client.getUser                         thrpt         4.943          ops/ms
Client.listUser                        thrpt         1.266          ops/ms
Client.createUser                       avgt         7.455           ms/op
Client.existUser                        avgt         3.530           ms/op
Client.getUser                          avgt         4.993           ms/op
Client.listUser                         avgt        19.274           ms/op
Client.createUser                     sample  4099   7.821 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample         1.880           ms/op
Client.createUser:createUser·p0.50    sample         7.578           ms/op
Client.createUser:createUser·p0.90    sample         8.503           ms/op
Client.createUser:createUser·p0.95    sample         9.961           ms/op
Client.createUser:createUser·p0.99    sample        20.054           ms/op
Client.createUser:createUser·p0.999   sample        23.488           ms/op
Client.createUser:createUser·p0.9999  sample        23.921           ms/op
Client.createUser:createUser·p1.00    sample        23.921           ms/op
Client.existUser                      sample  6441   4.977 ± 0.106   ms/op
Client.existUser:existUser·p0.00      sample         1.043           ms/op
Client.existUser:existUser·p0.50      sample         4.669           ms/op
Client.existUser:existUser·p0.90      sample         5.094           ms/op
Client.existUser:existUser·p0.95      sample         5.693           ms/op
Client.existUser:existUser·p0.99      sample        14.287           ms/op
Client.existUser:existUser·p0.999     sample        39.002           ms/op
Client.existUser:existUser·p0.9999    sample        39.191           ms/op
Client.existUser:existUser·p1.00      sample        39.191           ms/op
Client.getUser                        sample  6061   5.335 ± 0.098   ms/op
Client.getUser:getUser·p0.00          sample         2.351           ms/op
Client.getUser:getUser·p0.50          sample         4.948           ms/op
Client.getUser:getUser·p0.90          sample         5.800           ms/op
Client.getUser:getUser·p0.95          sample         7.246           ms/op
Client.getUser:getUser·p0.99          sample        17.200           ms/op
Client.getUser:getUser·p0.999         sample        24.281           ms/op
Client.getUser:getUser·p0.9999        sample        24.445           ms/op
Client.getUser:getUser·p1.00          sample        24.445           ms/op
Client.listUser                       sample  1738  18.224 ± 0.239   ms/op
Client.listUser:listUser·p0.00        sample         8.962           ms/op
Client.listUser:listUser·p0.50        sample        18.514           ms/op
Client.listUser:listUser·p0.90        sample        21.332           ms/op
Client.listUser:listUser·p0.95        sample        22.744           ms/op
Client.listUser:listUser·p0.99        sample        29.184           ms/op
Client.listUser:listUser·p0.999       sample        35.538           ms/op
Client.listUser:listUser·p0.9999      sample        35.586           ms/op
Client.listUser:listUser·p1.00        sample        35.586           ms/op
