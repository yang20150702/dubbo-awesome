# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.062 ops/ms
# Warmup Iteration   2: 2.129 ops/ms
# Warmup Iteration   3: 4.594 ops/ms
Iteration   1: 5.409 ops/ms
Iteration   2: 5.479 ops/ms
Iteration   3: 5.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.462 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (5.409, 5.462, 5.497), stdev = 0.046
  CI (99.9%): [4.615, 6.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.471 ops/ms
# Warmup Iteration   2: 4.753 ops/ms
# Warmup Iteration   3: 5.971 ops/ms
Iteration   1: 6.149 ops/ms
Iteration   2: 6.103 ops/ms
Iteration   3: 6.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.113 ±(99.9%) 0.580 ops/ms [Average]
  (min, avg, max) = (6.088, 6.113, 6.149), stdev = 0.032
  CI (99.9%): [5.533, 6.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.586 ops/ms
# Warmup Iteration   2: 4.114 ops/ms
# Warmup Iteration   3: 5.723 ops/ms
Iteration   1: 5.620 ops/ms
Iteration   2: 5.724 ops/ms
Iteration   3: 5.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.706 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (5.620, 5.706, 5.775), stdev = 0.079
  CI (99.9%): [4.262, 7.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.545 ops/ms
# Warmup Iteration   2: 3.980 ops/ms
# Warmup Iteration   3: 4.971 ops/ms
Iteration   1: 5.095 ops/ms
Iteration   2: 5.001 ops/ms
Iteration   3: 4.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.005 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (4.918, 5.005, 5.095), stdev = 0.088
  CI (99.9%): [3.396, 6.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.004 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 8.137 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.018 ms/op
Iteration   1: 5.852 ±(99.9%) 0.017 ms/op
Iteration   2: 5.518 ±(99.9%) 0.026 ms/op
Iteration   3: 5.601 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.657 ±(99.9%) 3.172 ms/op [Average]
  (min, avg, max) = (5.518, 5.657, 5.852), stdev = 0.174
  CI (99.9%): [2.486, 8.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.903 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.506 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.574 ±(99.9%) 0.007 ms/op
Iteration   1: 5.364 ±(99.9%) 0.015 ms/op
Iteration   2: 5.511 ±(99.9%) 0.009 ms/op
Iteration   3: 5.235 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.370 ±(99.9%) 2.521 ms/op [Average]
  (min, avg, max) = (5.235, 5.370, 5.511), stdev = 0.138
  CI (99.9%): [2.849, 7.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.765 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.680 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.828 ±(99.9%) 0.014 ms/op
Iteration   1: 5.793 ±(99.9%) 0.008 ms/op
Iteration   2: 5.735 ±(99.9%) 0.007 ms/op
Iteration   3: 5.507 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.678 ±(99.9%) 2.754 ms/op [Average]
  (min, avg, max) = (5.507, 5.678, 5.793), stdev = 0.151
  CI (99.9%): [2.924, 8.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.401 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.053 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.656 ±(99.9%) 0.019 ms/op
Iteration   1: 6.438 ±(99.9%) 0.012 ms/op
Iteration   2: 6.378 ±(99.9%) 0.016 ms/op
Iteration   3: 6.401 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.406 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (6.378, 6.406, 6.438), stdev = 0.030
  CI (99.9%): [5.857, 6.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.983 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 7.177 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 6.135 ±(99.9%) 0.027 ms/op
Iteration   1: 5.547 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.698 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  19.393 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 5.459 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.646 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  23.409 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 5.750 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.217 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  22.676 ms/op
                 createUser·p0.9999: 26.866 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171940
  mean =      5.583 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 52602 
    [ 5.000,  7.500) = 109775 
    [ 7.500, 10.000) = 7773 
    [10.000, 12.500) = 1181 
    [12.500, 15.000) = 357 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     26.667 ms/op
     p(99.9990) =     27.625 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.294 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.897 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.771 ±(99.9%) 0.024 ms/op
Iteration   1: 5.497 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   8.151 ms/op
                 existUser·p0.99:   11.289 ms/op
                 existUser·p0.999:  15.284 ms/op
                 existUser·p0.9999: 30.185 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   2: 5.437 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  27.794 ms/op
                 existUser·p0.9999: 35.659 ms/op
                 existUser·p1.00:   36.045 ms/op

Iteration   3: 5.560 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   6.726 ms/op
                 existUser·p0.95:   7.651 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  25.674 ms/op
                 existUser·p0.9999: 31.416 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174558
  mean =      5.497 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 59633 
    [ 5.000,  7.500) = 105296 
    [ 7.500, 10.000) = 7072 
    [10.000, 12.500) = 1752 
    [12.500, 15.000) = 507 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     34.019 ms/op
     p(99.9990) =     35.996 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.885 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.807 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.817 ±(99.9%) 0.022 ms/op
Iteration   1: 5.549 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.728 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  23.166 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   2: 5.664 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.130 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.520 ms/op
                 getUser·p0.99:   12.209 ms/op
                 getUser·p0.999:  26.068 ms/op
                 getUser·p0.9999: 29.526 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 5.510 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.880 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  20.756 ms/op
                 getUser·p0.9999: 31.601 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172195
  mean =      5.574 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 52493 
    [ 5.000,  7.500) = 109411 
    [ 7.500, 10.000) = 7627 
    [10.000, 12.500) = 1676 
    [12.500, 15.000) = 553 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     22.021 ms/op
     p(99.9900) =     30.631 ms/op
     p(99.9990) =     33.153 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.357 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 7.932 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.745 ±(99.9%) 0.026 ms/op
Iteration   1: 6.613 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.523 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.386 ms/op
                 listUser·p0.999:  28.168 ms/op
                 listUser·p0.9999: 31.413 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 6.329 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.457 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  28.148 ms/op
                 listUser·p0.9999: 30.816 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   3: 6.636 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  27.781 ms/op
                 listUser·p0.9999: 32.190 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147100
  mean =      6.523 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3516 
    [ 5.000,  7.500) = 126776 
    [ 7.500, 10.000) = 12599 
    [10.000, 12.500) = 2917 
    [12.500, 15.000) = 772 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 154 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      6.218 ms/op
     p(90.0000) =      7.651 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     28.112 ms/op
     p(99.9900) =     31.322 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.462 ± 0.847  ops/ms
ClientPb.existUser                       thrpt       3   6.113 ± 0.580  ops/ms
ClientPb.getUser                         thrpt       3   5.706 ± 1.444  ops/ms
ClientPb.listUser                        thrpt       3   5.005 ± 1.609  ops/ms
ClientPb.createUser                       avgt       3   5.657 ± 3.172   ms/op
ClientPb.existUser                        avgt       3   5.370 ± 2.521   ms/op
ClientPb.getUser                          avgt       3   5.678 ± 2.754   ms/op
ClientPb.listUser                         avgt       3   6.406 ± 0.548   ms/op
ClientPb.createUser                     sample  171940   5.583 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.163           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.667           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  174558   5.497 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.733           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.682           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.266           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.019           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  172195   5.574 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.292           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.873           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  147100   6.523 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.605           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.112           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.322           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899           ms/op
