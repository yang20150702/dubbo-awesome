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
# Warmup Iteration   1: 1.380 ops/ms
# Warmup Iteration   2: 3.403 ops/ms
# Warmup Iteration   3: 6.276 ops/ms
Iteration   1: 6.222 ops/ms
Iteration   2: 7.001 ops/ms
Iteration   3: 6.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.645 ±(99.9%) 7.175 ops/ms [Average]
  (min, avg, max) = (6.222, 6.645, 7.001), stdev = 0.393
  CI (99.9%): [≈ 0, 13.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 6.939 ops/ms
Iteration   1: 7.306 ops/ms
Iteration   2: 7.247 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.099 ±(99.9%) 5.652 ops/ms [Average]
  (min, avg, max) = (6.743, 7.099, 7.306), stdev = 0.310
  CI (99.9%): [1.447, 12.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 5.570 ops/ms
# Warmup Iteration   3: 6.325 ops/ms
Iteration   1: 6.326 ops/ms
Iteration   2: 6.745 ops/ms
Iteration   3: 6.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.591 ±(99.9%) 4.203 ops/ms [Average]
  (min, avg, max) = (6.326, 6.591, 6.745), stdev = 0.230
  CI (99.9%): [2.388, 10.793] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 5.645 ops/ms
# Warmup Iteration   3: 5.854 ops/ms
Iteration   1: 5.914 ops/ms
Iteration   2: 5.930 ops/ms
Iteration   3: 5.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.881 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (5.800, 5.881, 5.930), stdev = 0.071
  CI (99.9%): [4.591, 7.172] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.968 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.363 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.986 ±(99.9%) 0.015 ms/op
Iteration   1: 4.821 ±(99.9%) 0.012 ms/op
Iteration   2: 4.870 ±(99.9%) 0.010 ms/op
Iteration   3: 4.833 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.841 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (4.821, 4.841, 4.870), stdev = 0.025
  CI (99.9%): [4.377, 5.305] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.502 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.923 ±(99.9%) 0.006 ms/op
Iteration   1: 4.812 ±(99.9%) 0.012 ms/op
Iteration   2: 4.606 ±(99.9%) 0.014 ms/op
Iteration   3: 4.787 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.735 ±(99.9%) 2.050 ms/op [Average]
  (min, avg, max) = (4.606, 4.735, 4.812), stdev = 0.112
  CI (99.9%): [2.685, 6.785] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.288 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.821 ±(99.9%) 0.013 ms/op
Iteration   1: 4.672 ±(99.9%) 0.011 ms/op
Iteration   2: 4.697 ±(99.9%) 0.015 ms/op
Iteration   3: 4.671 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.680 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (4.671, 4.680, 4.697), stdev = 0.015
  CI (99.9%): [4.413, 4.948] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.476 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.232 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.415 ±(99.9%) 0.021 ms/op
Iteration   1: 5.517 ±(99.9%) 0.017 ms/op
Iteration   2: 5.543 ±(99.9%) 0.012 ms/op
Iteration   3: 5.345 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.468 ±(99.9%) 1.962 ms/op [Average]
  (min, avg, max) = (5.345, 5.468, 5.543), stdev = 0.108
  CI (99.9%): [3.507, 7.430] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.486 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.065 ±(99.9%) 0.020 ms/op
Iteration   1: 4.737 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.874 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   9.077 ms/op
                 createUser·p0.999:  16.791 ms/op
                 createUser·p0.9999: 35.602 ms/op
                 createUser·p1.00:   36.700 ms/op

Iteration   2: 4.703 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.089 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 29.583 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 4.540 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  21.975 ms/op
                 createUser·p0.9999: 26.475 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 205931
  mean =      4.659 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 158538 
    [ 5.000,  7.500) = 43940 
    [ 7.500, 10.000) = 2627 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     19.161 ms/op
     p(99.9900) =     29.813 ms/op
     p(99.9990) =     36.091 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.576 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.642 ±(99.9%) 0.015 ms/op
Iteration   1: 4.570 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.077 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 23.330 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 4.542 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  16.397 ms/op
                 existUser·p0.9999: 26.474 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 4.536 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   7.419 ms/op
                 existUser·p0.999:  15.776 ms/op
                 existUser·p0.9999: 25.818 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 210974
  mean =      4.550 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 172510 
    [ 5.000,  7.500) = 35608 
    [ 7.500, 10.000) = 2073 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     15.795 ms/op
     p(99.9900) =     25.752 ms/op
     p(99.9990) =     27.139 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.168 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.339 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.002 ±(99.9%) 0.014 ms/op
Iteration   1: 4.918 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   6.267 ms/op
                 getUser·p0.95:   7.578 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  17.064 ms/op
                 getUser·p0.9999: 25.313 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   2: 4.434 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  21.999 ms/op
                 getUser·p0.9999: 25.080 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 4.790 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.208 ms/op
                 getUser·p0.999:  16.100 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 204058
  mean =      4.705 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 154910 
    [ 5.000,  7.500) = 43915 
    [ 7.500, 10.000) = 3911 
    [10.000, 12.500) = 793 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     19.483 ms/op
     p(99.9900) =     25.120 ms/op
     p(99.9990) =     25.689 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 14.783 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.944 ±(99.9%) 0.020 ms/op
Iteration   1: 5.858 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  24.084 ms/op
                 listUser·p0.9999: 27.888 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 5.508 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.427 ms/op
                 listUser·p0.999:  20.539 ms/op
                 listUser·p0.9999: 25.171 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 5.444 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  17.636 ms/op
                 listUser·p0.9999: 19.567 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 171495
  mean =      5.598 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 44715 
    [ 5.000,  7.500) = 119311 
    [ 7.500, 10.000) = 5860 
    [10.000, 12.500) = 1017 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     26.986 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.645 ± 7.175  ops/ms
ClientPb.existUser                       thrpt       3   7.099 ± 5.652  ops/ms
ClientPb.getUser                         thrpt       3   6.591 ± 4.203  ops/ms
ClientPb.listUser                        thrpt       3   5.881 ± 1.291  ops/ms
ClientPb.createUser                       avgt       3   4.841 ± 0.464   ms/op
ClientPb.existUser                        avgt       3   4.735 ± 2.050   ms/op
ClientPb.getUser                          avgt       3   4.680 ± 0.267   ms/op
ClientPb.listUser                         avgt       3   5.468 ± 1.962   ms/op
ClientPb.createUser                     sample  205931   4.659 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.249           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.161           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  210974   4.550 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.795           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.752           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.230           ms/op
ClientPb.getUser                        sample  204058   4.705 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.483           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.247           ms/op
ClientPb.listUser                       sample  171495   5.598 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.578           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.677           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
