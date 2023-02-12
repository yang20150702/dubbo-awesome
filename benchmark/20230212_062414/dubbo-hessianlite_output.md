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
# Warmup Iteration   1: 0.557 ops/ms
Iteration   1: 1.276 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.276 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.624 ops/ms
Iteration   1: 3.863 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.863 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.180 ops/ms
Iteration   1: 2.583 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.583 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.589 ops/ms
Iteration   1: 0.892 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.892 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 25.697 ±(99.9%) 0.473 ms/op
Iteration   1: 16.740 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.740 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.959 ±(99.9%) 0.257 ms/op
Iteration   1: 7.336 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.336 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.595 ±(99.9%) 0.300 ms/op
Iteration   1: 7.866 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.866 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 41.118 ±(99.9%) 0.804 ms/op
Iteration   1: 29.721 ±(99.9%) 0.269 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  29.721 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.672 ±(99.9%) 0.590 ms/op
Iteration   1: 13.092 ±(99.9%) 0.338 ms/op
                 createUser·p0.00:   3.469 ms/op
                 createUser·p0.50:   11.567 ms/op
                 createUser·p0.90:   18.416 ms/op
                 createUser·p0.95:   22.577 ms/op
                 createUser·p0.99:   43.944 ms/op
                 createUser·p0.999:  44.827 ms/op
                 createUser·p0.9999: 44.827 ms/op
                 createUser·p1.00:   44.827 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2446
  mean =     13.092 ±(99.9%) 0.338 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 288 
    [10.000, 15.000) = 1776 
    [15.000, 20.000) = 233 
    [20.000, 25.000) = 69 
    [25.000, 30.000) = 44 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      3.469 ms/op
     p(50.0000) =     11.567 ms/op
     p(90.0000) =     18.416 ms/op
     p(95.0000) =     22.577 ms/op
     p(99.0000) =     43.944 ms/op
     p(99.9000) =     44.827 ms/op
     p(99.9900) =     44.827 ms/op
     p(99.9990) =     44.827 ms/op
     p(99.9999) =     44.827 ms/op
    p(100.0000) =     44.827 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.512 ±(99.9%) 0.373 ms/op
Iteration   1: 7.184 ±(99.9%) 0.146 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   7.193 ms/op
                 existUser·p0.90:   9.273 ms/op
                 existUser·p0.95:   11.338 ms/op
                 existUser·p0.99:   20.804 ms/op
                 existUser·p0.999:  25.505 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4480
  mean =      7.184 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 157 
    [ 2.500,  5.000) = 681 
    [ 5.000,  7.500) = 2032 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      7.193 ms/op
     p(90.0000) =      9.273 ms/op
     p(95.0000) =     11.338 ms/op
     p(99.0000) =     20.804 ms/op
     p(99.9000) =     25.505 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     25.821 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 17.877 ±(99.9%) 0.704 ms/op
Iteration   1: 8.639 ±(99.9%) 0.219 ms/op
                 getUser·p0.00:   2.785 ms/op
                 getUser·p0.50:   6.988 ms/op
                 getUser·p0.90:   13.484 ms/op
                 getUser·p0.95:   16.351 ms/op
                 getUser·p0.99:   22.879 ms/op
                 getUser·p0.999:  34.147 ms/op
                 getUser·p0.9999: 36.635 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3679
  mean =      8.639 ±(99.9%) 0.219 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 118 
    [ 5.000,  7.500) = 1995 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.785 ms/op
     p(50.0000) =      6.988 ms/op
     p(90.0000) =     13.484 ms/op
     p(95.0000) =     16.351 ms/op
     p(99.0000) =     22.879 ms/op
     p(99.9000) =     34.147 ms/op
     p(99.9900) =     36.635 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 46.162 ±(99.9%) 1.776 ms/op
Iteration   1: 26.749 ±(99.9%) 0.588 ms/op
                 listUser·p0.00:   10.912 ms/op
                 listUser·p0.50:   26.051 ms/op
                 listUser·p0.90:   33.096 ms/op
                 listUser·p0.95:   36.549 ms/op
                 listUser·p0.99:   52.620 ms/op
                 listUser·p0.999:  62.700 ms/op
                 listUser·p0.9999: 62.915 ms/op
                 listUser·p1.00:   62.915 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1192
  mean =     26.749 ±(99.9%) 0.588 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 183 
    [20.000, 25.000) = 218 
    [25.000, 30.000) = 544 
    [30.000, 35.000) = 166 
    [35.000, 40.000) = 44 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =     10.912 ms/op
     p(50.0000) =     26.051 ms/op
     p(90.0000) =     33.096 ms/op
     p(95.0000) =     36.549 ms/op
     p(99.0000) =     52.620 ms/op
     p(99.9000) =     62.700 ms/op
     p(99.9900) =     62.915 ms/op
     p(99.9990) =     62.915 ms/op
     p(99.9999) =     62.915 ms/op
    p(100.0000) =     62.915 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.276          ops/ms
Client.existUser                       thrpt         3.863          ops/ms
Client.getUser                         thrpt         2.583          ops/ms
Client.listUser                        thrpt         0.892          ops/ms
Client.createUser                       avgt        16.740           ms/op
Client.existUser                        avgt         7.336           ms/op
Client.getUser                          avgt         7.866           ms/op
Client.listUser                         avgt        29.721           ms/op
Client.createUser                     sample  2446  13.092 ± 0.338   ms/op
Client.createUser:createUser·p0.00    sample         3.469           ms/op
Client.createUser:createUser·p0.50    sample        11.567           ms/op
Client.createUser:createUser·p0.90    sample        18.416           ms/op
Client.createUser:createUser·p0.95    sample        22.577           ms/op
Client.createUser:createUser·p0.99    sample        43.944           ms/op
Client.createUser:createUser·p0.999   sample        44.827           ms/op
Client.createUser:createUser·p0.9999  sample        44.827           ms/op
Client.createUser:createUser·p1.00    sample        44.827           ms/op
Client.existUser                      sample  4480   7.184 ± 0.146   ms/op
Client.existUser:existUser·p0.00      sample         1.202           ms/op
Client.existUser:existUser·p0.50      sample         7.193           ms/op
Client.existUser:existUser·p0.90      sample         9.273           ms/op
Client.existUser:existUser·p0.95      sample        11.338           ms/op
Client.existUser:existUser·p0.99      sample        20.804           ms/op
Client.existUser:existUser·p0.999     sample        25.505           ms/op
Client.existUser:existUser·p0.9999    sample        25.821           ms/op
Client.existUser:existUser·p1.00      sample        25.821           ms/op
Client.getUser                        sample  3679   8.639 ± 0.219   ms/op
Client.getUser:getUser·p0.00          sample         2.785           ms/op
Client.getUser:getUser·p0.50          sample         6.988           ms/op
Client.getUser:getUser·p0.90          sample        13.484           ms/op
Client.getUser:getUser·p0.95          sample        16.351           ms/op
Client.getUser:getUser·p0.99          sample        22.879           ms/op
Client.getUser:getUser·p0.999         sample        34.147           ms/op
Client.getUser:getUser·p0.9999        sample        36.635           ms/op
Client.getUser:getUser·p1.00          sample        36.635           ms/op
Client.listUser                       sample  1192  26.749 ± 0.588   ms/op
Client.listUser:listUser·p0.00        sample        10.912           ms/op
Client.listUser:listUser·p0.50        sample        26.051           ms/op
Client.listUser:listUser·p0.90        sample        33.096           ms/op
Client.listUser:listUser·p0.95        sample        36.549           ms/op
Client.listUser:listUser·p0.99        sample        52.620           ms/op
Client.listUser:listUser·p0.999       sample        62.700           ms/op
Client.listUser:listUser·p0.9999      sample        62.915           ms/op
Client.listUser:listUser·p1.00        sample        62.915           ms/op
