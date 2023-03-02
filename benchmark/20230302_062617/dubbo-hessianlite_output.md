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
# Warmup Iteration   1: 0.645 ops/ms
Iteration   1: 1.314 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.314 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 1.206 ops/ms
Iteration   1: 3.529 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.529 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.265 ops/ms
Iteration   1: 2.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.606 ops/ms


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
# Warmup Iteration   1: 0.577 ops/ms
Iteration   1: 0.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.775 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 25.935 ±(99.9%) 0.719 ms/op
Iteration   1: 16.977 ±(99.9%) 0.170 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.977 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.479 ±(99.9%) 0.420 ms/op
Iteration   1: 11.912 ±(99.9%) 0.170 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.912 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.176 ±(99.9%) 0.429 ms/op
Iteration   1: 9.450 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.450 ms/op


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
# Warmup Iteration   1: 44.300 ±(99.9%) 1.223 ms/op
Iteration   1: 27.349 ±(99.9%) 0.434 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.349 ms/op


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
# Warmup Iteration   1: 19.686 ±(99.9%) 0.767 ms/op
Iteration   1: 12.355 ±(99.9%) 0.395 ms/op
                 createUser·p0.00:   4.596 ms/op
                 createUser·p0.50:   11.100 ms/op
                 createUser·p0.90:   18.448 ms/op
                 createUser·p0.95:   25.494 ms/op
                 createUser·p0.99:   43.057 ms/op
                 createUser·p0.999:  43.871 ms/op
                 createUser·p0.9999: 43.975 ms/op
                 createUser·p1.00:   43.975 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2574
  mean =     12.355 ±(99.9%) 0.395 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 654 
    [10.000, 15.000) = 1515 
    [15.000, 20.000) = 178 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 90 
    [30.000, 35.000) = 44 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      4.596 ms/op
     p(50.0000) =     11.100 ms/op
     p(90.0000) =     18.448 ms/op
     p(95.0000) =     25.494 ms/op
     p(99.0000) =     43.057 ms/op
     p(99.9000) =     43.871 ms/op
     p(99.9900) =     43.975 ms/op
     p(99.9990) =     43.975 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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
# Warmup Iteration   1: 13.704 ±(99.9%) 0.434 ms/op
Iteration   1: 7.819 ±(99.9%) 0.127 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   7.283 ms/op
                 existUser·p0.90:   9.445 ms/op
                 existUser·p0.95:   10.764 ms/op
                 existUser·p0.99:   21.332 ms/op
                 existUser·p0.999:  24.767 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4090
  mean =      7.819 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 121 
    [ 5.000,  7.500) = 2404 
    [ 7.500, 10.000) = 1183 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      7.283 ms/op
     p(90.0000) =      9.445 ms/op
     p(95.0000) =     10.764 ms/op
     p(99.0000) =     21.332 ms/op
     p(99.9000) =     24.767 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 17.238 ±(99.9%) 0.582 ms/op
Iteration   1: 7.885 ±(99.9%) 0.185 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   6.701 ms/op
                 getUser·p0.90:   12.242 ms/op
                 getUser·p0.95:   14.863 ms/op
                 getUser·p0.99:   25.199 ms/op
                 getUser·p0.999:  28.463 ms/op
                 getUser·p0.9999: 29.688 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4076
  mean =      7.885 ±(99.9%) 0.185 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 192 
    [ 5.000,  7.500) = 2444 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      6.701 ms/op
     p(90.0000) =     12.242 ms/op
     p(95.0000) =     14.863 ms/op
     p(99.0000) =     25.199 ms/op
     p(99.9000) =     28.463 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     29.688 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 39.786 ±(99.9%) 1.778 ms/op
Iteration   1: 31.131 ±(99.9%) 0.715 ms/op
                 listUser·p0.00:   15.876 ms/op
                 listUser·p0.50:   29.770 ms/op
                 listUser·p0.90:   37.421 ms/op
                 listUser·p0.95:   42.346 ms/op
                 listUser·p0.99:   66.829 ms/op
                 listUser·p0.999:  70.252 ms/op
                 listUser·p0.9999: 70.255 ms/op
                 listUser·p1.00:   70.255 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1016
  mean =     31.131 ±(99.9%) 0.715 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 417 
    [30.000, 35.000) = 286 
    [35.000, 40.000) = 157 
    [40.000, 45.000) = 20 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 8 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =     15.876 ms/op
     p(50.0000) =     29.770 ms/op
     p(90.0000) =     37.421 ms/op
     p(95.0000) =     42.346 ms/op
     p(99.0000) =     66.829 ms/op
     p(99.9000) =     70.252 ms/op
     p(99.9900) =     70.255 ms/op
     p(99.9990) =     70.255 ms/op
     p(99.9999) =     70.255 ms/op
    p(100.0000) =     70.255 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.314          ops/ms
Client.existUser                       thrpt         3.529          ops/ms
Client.getUser                         thrpt         2.606          ops/ms
Client.listUser                        thrpt         0.775          ops/ms
Client.createUser                       avgt        16.977           ms/op
Client.existUser                        avgt        11.912           ms/op
Client.getUser                          avgt         9.450           ms/op
Client.listUser                         avgt        27.349           ms/op
Client.createUser                     sample  2574  12.355 ± 0.395   ms/op
Client.createUser:createUser·p0.00    sample         4.596           ms/op
Client.createUser:createUser·p0.50    sample        11.100           ms/op
Client.createUser:createUser·p0.90    sample        18.448           ms/op
Client.createUser:createUser·p0.95    sample        25.494           ms/op
Client.createUser:createUser·p0.99    sample        43.057           ms/op
Client.createUser:createUser·p0.999   sample        43.871           ms/op
Client.createUser:createUser·p0.9999  sample        43.975           ms/op
Client.createUser:createUser·p1.00    sample        43.975           ms/op
Client.existUser                      sample  4090   7.819 ± 0.127   ms/op
Client.existUser:existUser·p0.00      sample         2.372           ms/op
Client.existUser:existUser·p0.50      sample         7.283           ms/op
Client.existUser:existUser·p0.90      sample         9.445           ms/op
Client.existUser:existUser·p0.95      sample        10.764           ms/op
Client.existUser:existUser·p0.99      sample        21.332           ms/op
Client.existUser:existUser·p0.999     sample        24.767           ms/op
Client.existUser:existUser·p0.9999    sample        25.559           ms/op
Client.existUser:existUser·p1.00      sample        25.559           ms/op
Client.getUser                        sample  4076   7.885 ± 0.185   ms/op
Client.getUser:getUser·p0.00          sample         1.694           ms/op
Client.getUser:getUser·p0.50          sample         6.701           ms/op
Client.getUser:getUser·p0.90          sample        12.242           ms/op
Client.getUser:getUser·p0.95          sample        14.863           ms/op
Client.getUser:getUser·p0.99          sample        25.199           ms/op
Client.getUser:getUser·p0.999         sample        28.463           ms/op
Client.getUser:getUser·p0.9999        sample        29.688           ms/op
Client.getUser:getUser·p1.00          sample        29.688           ms/op
Client.listUser                       sample  1016  31.131 ± 0.715   ms/op
Client.listUser:listUser·p0.00        sample        15.876           ms/op
Client.listUser:listUser·p0.50        sample        29.770           ms/op
Client.listUser:listUser·p0.90        sample        37.421           ms/op
Client.listUser:listUser·p0.95        sample        42.346           ms/op
Client.listUser:listUser·p0.99        sample        66.829           ms/op
Client.listUser:listUser·p0.999       sample        70.252           ms/op
Client.listUser:listUser·p0.9999      sample        70.255           ms/op
Client.listUser:listUser·p1.00        sample        70.255           ms/op
